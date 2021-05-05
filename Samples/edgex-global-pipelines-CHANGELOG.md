
<a name="x.y.z"></a>
## [x.y.z] - 0001-01-01

<a name="stable"></a>
## [stable] - 2021-04-29

<a name="experimental"></a>
## [experimental] - 2021-04-29

<a name="v1.0.191"></a>
## [v1.0.191] - 2021-04-29
### Features ✨
- make Go 1.16 the default Go version ([#0864875](/commits/0864875))

<a name="v1.0.190"></a>
## [v1.0.190] - 2021-04-27
### Bug Fixes 🐛
- update permission for build artifacts ([#302d3fe](/commits/302d3fe))

<a name="v1.0.189"></a>
## [v1.0.189] - 2021-04-19

<a name="v1.0.188"></a>
## [v1.0.188] - 2021-03-25
### Doc
- Update the documentation for the following pre-built pipelines: edgeXBuildGoMod,edgeXBuildDocker,edgeXBuildCApp ([#829e728](/commits/829e728))

<a name="v1.0.187"></a>
## [v1.0.187] - 2021-03-24
### Features ✨
- only fail stage artifact stage if possible to build artifact ([#324](/issues/324)) ([#606c6f7](/commits/606c6f7))

<a name="v1.0.186"></a>
## [v1.0.186] - 2021-03-17
### Features ✨
- **snap:** replace optimization patch with new script ([#f452aa2](/commits/f452aa2))

<a name="v1.0.185"></a>
## [v1.0.185] - 2021-03-10
### Documentation 📖
- update documentation for edgeXBuildGoApp and edgeXBuildGoParallel ([#4431695](/commits/4431695))

<a name="v1.0.184"></a>
## [v1.0.184] - 2021-03-02
### Bug Fixes 🐛
- jobDetails should be defaulted to null ([#92121ae](/commits/92121ae))

<a name="v1.0.183"></a>
## [v1.0.183] - 2021-02-26
### Bug Fixes 🐛
- reference to old email method ([#dbec358](/commits/dbec358))

<a name="v1.0.182"></a>
## [v1.0.182] - 2021-02-25
### Features ✨
- Add ability to send HTML emails on build failure ([#5491795](/commits/5491795))

<a name="v1.0.181"></a>
## [v1.0.181] - 2021-02-23

<a name="v1.0.180"></a>
## [v1.0.180] - 2021-02-12

<a name="v1.0.179"></a>
## [v1.0.179] - 2021-01-19
### Features ✨
- Go modules bump pre-release version now ([#e47fc61](/commits/e47fc61))

<a name="v1.0.178"></a>
## [v1.0.178] - 2021-01-15

<a name="v1.0.177"></a>
## [v1.0.177] - 2021-01-13
### Bug Fixes 🐛
- use --data-binary instead of -d ([#a2387a4](/commits/a2387a4))

<a name="v1.0.176"></a>
## [v1.0.176] - 2021-01-13
### Bug
- publish via curl [@file](:/file) rather than raw cat ([#80a1292](/commits/80a1292))

<a name="v1.0.175"></a>
## [v1.0.175] - 2021-01-13
### Reverts
- feat: remove docker image prefix/suffix


<a name="v1.0.174"></a>
## [v1.0.174] - 2021-01-13
### Features ✨
- remove docker image prefix/suffix ([#a6bf1fb](/commits/a6bf1fb))

<a name="v1.0.173"></a>
## [v1.0.173] - 2020-12-16
### Features ✨
- allow Snyk docker scans to be disabled via config ([#c0b4a16](/commits/c0b4a16))

<a name="v1.0.172"></a>
## [v1.0.172] - 2020-12-08
### Features ✨
- **snap:** Use new native build script ([#7ec42ef](/commits/7ec42ef))

<a name="v1.0.171"></a>
## [v1.0.171] - 2020-12-04
### Bug Fixes 🐛
- revert go module semver bump change ([#e4f56fd](/commits/e4f56fd))

<a name="v1.0.170"></a>
## [v1.0.170] - 2020-12-04
### Features ✨
- go modules no longer bump patch semver ([#00a5baa](/commits/00a5baa))

<a name="v1.0.169"></a>
## [v1.0.169] - 2020-11-30
### Bug Fixes 🐛
- require check before running edgeXDockerLogin ([#0f932be](/commits/0f932be))

<a name="v1.0.168"></a>
## [v1.0.168] - 2020-11-20
### Features ✨
- **ci:** add verification and force feature of docker images in release flow. ([#287](/issues/287)) ([#0d18be6](/commits/0d18be6))

<a name="v1.0.167"></a>
## [v1.0.167] - 2020-11-19
### Bug Fixes 🐛
- add function to enable docker registry mirror ([#03772cd](/commits/03772cd))

<a name="v1.0.166"></a>
## [v1.0.166] - 2020-11-18
### Bug
- fix Snyk C scan image name ([#0f72fdc](/commits/0f72fdc))

<a name="v1.0.165"></a>
## [v1.0.165] - 2020-11-18
### Features ✨
- add hanoi to valid release stream ([#d4ffae0](/commits/d4ffae0))

<a name="v1.0.164"></a>
## v1.0.164 - 2020-11-12
### Bug
- fix customWorkspace issue ([#1935db7](/commits/1935db7))
### Style
- update code style and include stashName ([#a1aae03](/commits/a1aae03))
### Bugfix
- **groovy:** revert prev logic and add release check ([#04f402e](/commits/04f402e))
### US5858
- EdgeX DevOps: figure out how to lint groovy code ([#fc34933](/commits/fc34933))
### Features ✨
- inline Snyk docker image scan ([#8c43cc0](/commits/8c43cc0))
- add geneva as a valid release stream ([#e1aafe0](/commits/e1aafe0))
- use dockerfile as agent for mkdocs stage ([#16dd1a8](/commits/16dd1a8))
- documentation generation for edgex-global-pipelines Signed-off-by: Chinu Joy <chinu.joy[@intel](:/intel).com> ([#d717988](/commits/d717988))
- add rebuilding artifact as part of edgeXRelease ([#67d2549](/commits/67d2549))
- add docker support for lfInfraShipLogs ([#8552ef8](/commits/8552ef8))
- add new env var for archiving artifacts ([#08645ad](/commits/08645ad))
- add build icon on README ([#e0e6c4e](/commits/e0e6c4e))
- update default version of Go to 1.15 ([#23af239](/commits/23af239))
- add new option for Go 1.15 base image ([#7fa99f5](/commits/7fa99f5))
- update sysstat steps after upstream image change ([#99ba8d1](/commits/99ba8d1))
- add dockerBuildArgs config parameter ([#6ed5fb5](/commits/6ed5fb5))
- Snap modifications ([#0f08fef](/commits/0f08fef))
- Add support for parallel test execution ([#db9b0a7](/commits/db9b0a7))
- **GlobalFunction:** add edgeXSwaggerPublish to wrap existing shell scripts for SwaggerHub publishing ([#44a599f](/commits/44a599f))
- **jenkins:** Shared library for github-pages publish ([#8d21736](/commits/8d21736))
### Revert
- Disable Snap arm64 stage ([#f459401](/commits/f459401))
### Bug Fixes 🐛
- launch isolated node for amd64 builds ([#82bb14f](/commits/82bb14f))
- Commit message in gh-pages branch ([#1e61f79](/commits/1e61f79))
- Always run the codecov test/scan stages ([#f2a8db2](/commits/f2a8db2))
- log publishing errors should not fail the builds ([#f943b7d](/commits/f943b7d))
- permission change for .semver directory ([#99a7f19](/commits/99a7f19))
- update script for html directory ([#8580011](/commits/8580011))
- publish on isolated node ([#40cfd20](/commits/40cfd20))
- issue with CodeCov uploader ([#b2f08c2](/commits/b2f08c2))
- issue with env.ARCH in buildArtifact ([#4b6d995](/commits/4b6d995))
- make DRY_RUN default to false unless explicitly defined. ([#d899751](/commits/d899751))
- go version needs to be wrapped within base image ([#d2451ae](/commits/d2451ae))
- add option for git-semver arm64 docker image ([#3639071](/commits/3639071))
- codecov stage should not run on master ([#fc0a20e](/commits/fc0a20e))
- pushAll ignores arm64 image name suffix ([#d3c920c](/commits/d3c920c))
### Code Refactoring ♻
- docker login in all prep stages ([#f79db5f](/commits/f79db5f))
- remove markdown files in libraries ([#c0101d5](/commits/c0101d5))
- reorganize markdown files ([#7199773](/commits/7199773))
- move go version to prep stage ([#6aece77](/commits/6aece77))
### Documentation 📖
- Init edgeXBuildGoParallel documentation ([#8bab9e3](/commits/8bab9e3))
- New tutorial on docker usage ([#01db4e7](/commits/01db4e7))
- update header with WIP ([#501823a](/commits/501823a))
- update named branch documentation ([#b3462b4](/commits/b3462b4))
- update pr template to add new dependencies question ([#6a81fdb](/commits/6a81fdb))
- **jenkins:** Rename and consolidate unit testing best practices ([#fa303e6](/commits/fa303e6))
- **jenkins:** Add documentation for unit testing prescriptive guidance ([#bd7d650](/commits/bd7d650))
- **jenkins:** Add documentation for using PR commit hash for Jenkins sandbox testing. ([#1836d10](/commits/1836d10))
### Other changes
- update global-jjb to match ci-management ([#13207bf](/commits/13207bf))
### Continuous Integration 🔄
- remove GOTESTFLAGS ([#3c218c9](/commits/3c218c9))
- update snap stage for C apps ([#0174f95](/commits/0174f95))
- **groovy:** update previous to origin/HEAD ([#f61d50f](/commits/f61d50f))

[Unreleased]: /compare/x.y.z...HEAD
[x.y.z]: /compare/stable...x.y.z
[stable]: /compare/experimental...stable
[experimental]: /compare/v1.0.191...experimental
[v1.0.191]: /compare/v1.0.190...v1.0.191
[v1.0.190]: /compare/v1.0.189...v1.0.190
[v1.0.189]: /compare/v1.0.188...v1.0.189
[v1.0.188]: /compare/v1.0.187...v1.0.188
[v1.0.187]: /compare/v1.0.186...v1.0.187
[v1.0.186]: /compare/v1.0.185...v1.0.186
[v1.0.185]: /compare/v1.0.184...v1.0.185
[v1.0.184]: /compare/v1.0.183...v1.0.184
[v1.0.183]: /compare/v1.0.182...v1.0.183
[v1.0.182]: /compare/v1.0.181...v1.0.182
[v1.0.181]: /compare/v1.0.180...v1.0.181
[v1.0.180]: /compare/v1.0.179...v1.0.180
[v1.0.179]: /compare/v1.0.178...v1.0.179
[v1.0.178]: /compare/v1.0.177...v1.0.178
[v1.0.177]: /compare/v1.0.176...v1.0.177
[v1.0.176]: /compare/v1.0.175...v1.0.176
[v1.0.175]: /compare/v1.0.174...v1.0.175
[v1.0.174]: /compare/v1.0.173...v1.0.174
[v1.0.173]: /compare/v1.0.172...v1.0.173
[v1.0.172]: /compare/v1.0.171...v1.0.172
[v1.0.171]: /compare/v1.0.170...v1.0.171
[v1.0.170]: /compare/v1.0.169...v1.0.170
[v1.0.169]: /compare/v1.0.168...v1.0.169
[v1.0.168]: /compare/v1.0.167...v1.0.168
[v1.0.167]: /compare/v1.0.166...v1.0.167
[v1.0.166]: /compare/v1.0.165...v1.0.166
[v1.0.165]: /compare/v1.0.164...v1.0.165
