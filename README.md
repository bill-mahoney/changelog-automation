# changelog-automation

Changelog Automation Explore and Analysis

- [changelog-automation](#changelog-automation)
  - [Intro](#intro)
  - [git-chglog](#git-chglog)
    - [Summary](#summary)
    - [Configuration](#configuration)
      - [**`config.yaml`**](#configyaml)
    - [Execution](#execution)
    - [Output](#output)
  - [semantic-release](#semantic-release)
    - [Summary](#summary-1)
    - [Configuration](#configuration-1)
      - [**`.releaserc`**](#releaserc)
    - [Execution](#execution-1)
    - [Output](#output-1)
  - [Next Steps](#next-steps)

## Intro

- Conventional Commits are a standard method of formatting git commit messages.
  - Able to determine version (Major.Minor.Patch) of the next release based on commit messages since the last release.
  - [Conventional Commit Specification](https://www.conventionalcommits.org/en/v1.0.0/#specification)
- EdgeX adopted Conventional Commits on all repositories in H2 2020. 
  - [EdgeX Committing Code Guidelines](https://wiki.edgexfoundry.org/display/FA/Committing+Code+Guidelines#CommittingCodeGuidelines-ConventionalCommits)
- Conventional Commits enables changelog automation that can be done at release time or after any new PR is merged (ongoing).
  
**This demo was run from a forked: [app-functions-sdk-go@v2.0.0-dev.43](https://github.com/edgexfoundry/app-functions-sdk-go/tree/v2.0.0-dev.43)**

## git-chglog

GitHub: <https://github.com/git-chglog/git-chglog>

### Summary

- Lightweight, single binary application written in golang.
- Inspired by [conventional-changelog](https://github.com/conventional-changelog/conventional-changelog) project
- Docker image provided.

### Configuration

Config File (default settings): `/app-functions-sdk-go/.chglog/config.yaml`.

#### **`config.yaml`**

```yaml
style: github
template: CHANGELOG.tpl.md
info:
  title: CHANGELOG
  repository_url: https://github.com/edgexfoundry/app-functions-sdk-go
options:
  commits:
    # filters:
    #   Type:
    #     - feat
    #     - fix
    #     - perf
    #     - refactor
  commit_groups:
    # title_maps:
    #   feat: Features
    #   fix: Bug Fixes
    #   perf: Performance Improvements
    #   refactor: Code Refactoring
  header:
    pattern: "^(\\w*)(?:\\(([\\w\\$\\.\\-\\*\\s]*)\\))?\\:\\s(.*)$"
    pattern_maps:
      - Type
      - Scope
      - Subject
  notes:
    keywords:
      - BREAKING CHANGE
```

### Execution

```bash
git clone git@github.com:edgexfoundry/app-functions-sdk-go.git
cd app-functions-sdk-go
docker run -v "$PWD":/workdir quay.io/git-chglog/git-chglog --output git-chglog-changelog.md
```

### Output

[git-chglog-changelog.md](git-chglog-changelog.md)

Output Notes:

- Chronological ordering.
- Unreleased commits (pre-release tags) are all separated. When release occurs the next run of git-chglog will then group the unreleased versions together under the proper released version. (In this example, v2.0.0-dev-1 .. v2.0.0-dev43 will be under v2.0.0)
- Shows the PR # but not the linked issue # it closes.
- Flexible argument parameters to automate specific ranges that we'd like:

```bash
git-chglog 1.0.0..2.0.0
```



## semantic-release

GitHub <https://github.com/semantic-release/changelog>

### Summary

- [Semantic-release](https://github.com/semantic-release/semantic-release) is an npm/javascript application for version management and package publishing.
- [changelog](https://github.com/semantic-release/changelog) is a plugin for semantic-release to automate changelog generation
- Heavy weight solution for just changelog. Much more intrusive.
  - Requires write permission to the repo before a changelog can be created.
  - Release **must** be done before a changelog can be created. Tagging the releaase is required before a changelog can be generated.
    - Can do some hacks with a local on-disk remote as a workaround. Spotify [argued](https://github.com/semantic-release/semantic-release/issues/964) with maintainers to add feature with no luck.
- Semantic-release doesn't have an official docker container.

### Configuration

Configured within the standard semantic release configuration file `/app-functions-sdk-go/.releaserc` that lives at the root of the repository.

#### **`.releaserc`**
```json
{
  "noVerify": true,
  "dryRun": false,
  "ci": false,
  "debug": true,
  "repositoryUrl": "https://github.com/edgexfoundry/app-functions-sdk-go.git",
  "plugins": [
    "@semantic-release/commit-analyzer",
    "@semantic-release/release-notes-generator",
    [
      "@semantic-release/changelog",
      {
        "changelogFile": "semantic-release-changelog.md"
      }
    ]
  ]
}
```

### Execution
```bash
git clone git@github.com:edgexfoundry/app-functions-sdk-go.git
cd app-functions-sdk-go
docker run -w /app -v $(pwd):/app gtramontina/semantic-release:17.4.2
```

### Output

[semantic-release-changelog.md](semantic-release-changelog.md)

Output Notes:

- Only creates changelog for the released version, does not have a "running" list of changes from prior releases.
- Doesn't seem to support creating a changelog from TagA to TagB.
- Shows the PR **and** which Issue # it closes if described in PR.
- BREAKING CHANGES show lots of "Signed-off-by: ..." messages as part of the changelog.

## Next Steps

1) When do we create the changelog?

   - At release time? Changelog would be summary of all changes since last release. (e.g. add automation to the edgexrelease function in edgex-global-pipelines)
   - At build time? Changelog generated as PR gets built onto `main/master`. (e.g. add automation to the edgexBuild*.groovy pipelines within edgex-global-pipelines)

2) What does the automation do with the created changelog?

    - Commit back to the repository?
    - Upload the changelog?
