
<a name="x.y.z"></a>
## [x.y.z] - 2021-05-05
### Features ✨
- Add GenerateConsulToken API to SecretClient interface ([#6432e0d](https://github.com/edgexfoundry/go-mod-secrets/commits/6432e0d))
- **security:** Add Generate Registry Token API for secretstore client ([#5e2f4d4](https://github.com/edgexfoundry/go-mod-secrets/commits/5e2f4d4))
### Bug Fixes 🐛
- reduce the resource constraints as too many semaphores costs now ([#1b8a009](https://github.com/edgexfoundry/go-mod-secrets/commits/1b8a009))
- address Lenny's PR comments ([#ec8a875](https://github.com/edgexfoundry/go-mod-secrets/commits/ec8a875))
- **security:** Fix JSON structure of token self response ([#d9d1b45](https://github.com/edgexfoundry/go-mod-secrets/commits/d9d1b45))
### Code Refactoring ♻
- Tweaked GenerateConsulToken to use service's own token ([#fe93ff0](https://github.com/edgexfoundry/go-mod-secrets/commits/fe93ff0))
- Updated unit tests per PR discussion ([#3449eae](https://github.com/edgexfoundry/go-mod-secrets/commits/3449eae))
- Chnage unseal to just take KeysBase64 ([#f998050](https://github.com/edgexfoundry/go-mod-secrets/commits/f998050))
- More rework form PR review. ([#84275d8](https://github.com/edgexfoundry/go-mod-secrets/commits/84275d8))
- Fixup from PR feedback ([#6b3765b](https://github.com/edgexfoundry/go-mod-secrets/commits/6b3765b))
- Refactor to be proper abstraction of a SecretStore ([#89b3b67](https://github.com/edgexfoundry/go-mod-secrets/commits/89b3b67))
    ```
    BREAKING CHANGE:
    All existing SecretStore configuration must add `Type = 'vault'`
    ```
- Consume V2 go-mod-secrets ([#1668bd9](https://github.com/edgexfoundry/go-mod-secrets/commits/1668bd9))
- Make module a V2 Go Module ([#a525e5b](https://github.com/edgexfoundry/go-mod-secrets/commits/a525e5b))
### Documentation 📖
- Add badges to readme ([#5a9df2d](https://github.com/edgexfoundry/go-mod-secrets/commits/5a9df2d))
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#3544300](https://github.com/edgexfoundry/go-mod-secrets/commits/3544300))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#e6519c8](https://github.com/edgexfoundry/go-mod-secrets/commits/e6519c8))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#47ef1dc](https://github.com/edgexfoundry/go-mod-secrets/commits/47ef1dc))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#b50891a](https://github.com/edgexfoundry/go-mod-secrets/commits/b50891a))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#9757fd8](https://github.com/edgexfoundry/go-mod-secrets/commits/9757fd8))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#93ddefd](https://github.com/edgexfoundry/go-mod-secrets/commits/93ddefd))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#e47299e](https://github.com/edgexfoundry/go-mod-secrets/commits/e47299e))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#f835d59](https://github.com/edgexfoundry/go-mod-secrets/commits/f835d59))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#7a9458c](https://github.com/edgexfoundry/go-mod-secrets/commits/7a9458c))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#25705e2](https://github.com/edgexfoundry/go-mod-secrets/commits/25705e2))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#61fb651](https://github.com/edgexfoundry/go-mod-secrets/commits/61fb651))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#a419033](https://github.com/edgexfoundry/go-mod-secrets/commits/a419033))

<a name="v0.0.33"></a>
## [v0.0.33] - 2021-01-19

<a name="v0.0.32"></a>
## [v0.0.32] - 2021-01-12

<a name="v0.0.31"></a>
## [v0.0.31] - 2021-01-07

<a name="v0.0.30"></a>
## [v0.0.30] - 2021-01-07
### Code Refactoring ♻
- Resolve compiler errors in unit test when using latest go-mod-core-contracts ([#7271790](https://github.com/edgexfoundry/go-mod-secrets/commits/7271790))

<a name="v0.0.29"></a>
## [v0.0.29] - 2020-12-15

<a name="v0.0.28"></a>
## [v0.0.28] - 2020-12-15
### Bug Fixes 🐛
- Fix failing unit tests ([#1ee4d73](https://github.com/edgexfoundry/go-mod-secrets/commits/1ee4d73))
### Code Refactoring ♻
- Fixup from PR review comments. ([#5317c89](https://github.com/edgexfoundry/go-mod-secrets/commits/5317c89))
- Implement better abstraction for use in Secret Provider ([#62837fd](https://github.com/edgexfoundry/go-mod-secrets/commits/62837fd))

<a name="v0.0.27"></a>
## [v0.0.27] - 2020-11-25

<a name="v0.0.26"></a>
## [v0.0.26] - 2020-10-26

<a name="v0.0.25"></a>
## [v0.0.25] - 2020-10-20

<a name="v0.0.24"></a>
## [v0.0.24] - 2020-10-13

<a name="v0.0.23"></a>
## [v0.0.23] - 2020-10-01

<a name="v0.0.22"></a>
## [v0.0.22] - 2020-09-24
### Build 👷
- **all:** Enable use of DependaBot to maintain Go dependencies ([#aad16d8](https://github.com/edgexfoundry/go-mod-secrets/commits/aad16d8))

<a name="v0.0.21"></a>
## [v0.0.21] - 2020-09-16
### Bug Fixes 🐛
- Remove trailing slash from vault URL to avoid 400 error ([#1487bb7](https://github.com/edgexfoundry/go-mod-secrets/commits/1487bb7))

<a name="v0.0.20"></a>
## [v0.0.20] - 2020-09-11
### Build 👷
- update to go 1.15 ([#e59ca73](https://github.com/edgexfoundry/go-mod-secrets/commits/e59ca73))

<a name="v0.0.19"></a>
## [v0.0.19] - 2020-07-28
### Documentation 📖
- Update PR Template ([#3cab513](https://github.com/edgexfoundry/go-mod-secrets/commits/3cab513))

<a name="v0.0.18"></a>
## [v0.0.18] - 2020-05-12

<a name="v0.0.17"></a>
## [v0.0.17] - 2020-02-24

<a name="v0.0.16"></a>
## [v0.0.16] - 2020-02-13
### Build 👷
- Update relevant files in go-mod-secrets for Go 1.13 compiler. ([#89b012e](https://github.com/edgexfoundry/go-mod-secrets/commits/89b012e))

<a name="v0.0.15"></a>
## [v0.0.15] - 2020-01-31

<a name="v0.0.14"></a>
## [v0.0.14] - 2020-01-16

<a name="v0.0.13"></a>
## [v0.0.13] - 2020-01-07

<a name="v0.0.12"></a>
## [v0.0.12] - 2020-01-07

<a name="v0.0.11"></a>
## [v0.0.11] - 2019-12-28

<a name="v0.0.10"></a>
## [v0.0.10] - 2019-11-09

<a name="v0.0.9"></a>
## [v0.0.9] - 2019-11-06

<a name="v0.0.8"></a>
## [v0.0.8] - 2019-11-06

<a name="v0.0.7"></a>
## [v0.0.7] - 2019-10-14

<a name="v0.0.6"></a>
## [v0.0.6] - 2019-09-24

<a name="v0.0.5"></a>
## [v0.0.5] - 2019-09-24

<a name="v0.0.4"></a>
## [v0.0.4] - 2019-09-20

<a name="v0.0.3"></a>
## [v0.0.3] - 2019-09-19

<a name="v0.0.2"></a>
## [v0.0.2] - 2019-09-17

<a name="v0.0.1"></a>
## [v0.0.1] - 2019-09-10

<a name="v0.0.0"></a>
## v0.0.0 - 2019-08-23

[Unreleased]: https://github.com/edgexfoundry/go-mod-secrets/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.33...x.y.z
[v0.0.33]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.32...v0.0.33
[v0.0.32]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.31...v0.0.32
[v0.0.31]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.30...v0.0.31
[v0.0.30]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.29...v0.0.30
[v0.0.29]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.28...v0.0.29
[v0.0.28]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.27...v0.0.28
[v0.0.27]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.26...v0.0.27
[v0.0.26]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.25...v0.0.26
[v0.0.25]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.24...v0.0.25
[v0.0.24]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.23...v0.0.24
[v0.0.23]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.22...v0.0.23
[v0.0.22]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.21...v0.0.22
[v0.0.21]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.20...v0.0.21
[v0.0.20]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.19...v0.0.20
[v0.0.19]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.18...v0.0.19
[v0.0.18]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.17...v0.0.18
[v0.0.17]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.16...v0.0.17
[v0.0.16]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.15...v0.0.16
[v0.0.15]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.14...v0.0.15
[v0.0.14]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.13...v0.0.14
[v0.0.13]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.12...v0.0.13
[v0.0.12]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.11...v0.0.12
[v0.0.11]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.10...v0.0.11
[v0.0.10]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.9...v0.0.10
[v0.0.9]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.8...v0.0.9
[v0.0.8]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.7...v0.0.8
[v0.0.7]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.6...v0.0.7
[v0.0.6]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.5...v0.0.6
[v0.0.5]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.4...v0.0.5
[v0.0.4]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.3...v0.0.4
[v0.0.3]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.2...v0.0.3
[v0.0.2]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.1...v0.0.2
[v0.0.1]: https://github.com/edgexfoundry/go-mod-secrets/compare/v0.0.0...v0.0.1
