
<a name="x.y.z"></a>
## [x.y.z] - 2021-04-30
### Features ✨
- Remove Logging configuration ([#c973575](https://github.com/edgexfoundry/device-rest-go/commits/c973575))
### Bug Fixes 🐛
- use correct service key in SecretStore paths ([#23b2ca7](https://github.com/edgexfoundry/device-rest-go/commits/23b2ca7))
- Add Type='vault' to [SecretStore] config ([#99e6da9](https://github.com/edgexfoundry/device-rest-go/commits/99e6da9))
### Code Refactoring ♻
- use v2 device-sdk ([#8b511d7](https://github.com/edgexfoundry/device-rest-go/commits/8b511d7))
### Documentation 📖
- update README for v2 ([#f51f5ca](https://github.com/edgexfoundry/device-rest-go/commits/f51f5ca))
- Add badges to readme ([#972f9a5](https://github.com/edgexfoundry/device-rest-go/commits/972f9a5))
### Build 👷
- update build files for v2 ([#a01389d](https://github.com/edgexfoundry/device-rest-go/commits/a01389d))

<a name="v1.2.1"></a>
## [v1.2.1] - 2021-02-02
### Features ✨
- **snap:** add startup-duration and startup-interval configure options ([#4b44503](https://github.com/edgexfoundry/device-rest-go/commits/4b44503))
### Build 👷
- **deps:** Bump github.com/edgexfoundry/device-sdk-go ([#70](https://github.com/edgexfoundry/device-rest-go/issues/70)) ([#abd24f1](https://github.com/edgexfoundry/device-rest-go/commits/abd24f1))
### Continuous Integration 🔄
- add semantic.yml for commit linting, update PR template to latest ([#c3aa815](https://github.com/edgexfoundry/device-rest-go/commits/c3aa815))
- standardize dockerfiles ([#998a81b](https://github.com/edgexfoundry/device-rest-go/commits/998a81b))

<a name="v1.2.0"></a>
## [v1.2.0] - 2020-11-18
### Doc
- correct build instructions ([#36](https://github.com/edgexfoundry/device-rest-go/issues/36)) ([#a96498e](https://github.com/edgexfoundry/device-rest-go/commits/a96498e))
### Bug Fixes 🐛
- **snap:** Update snap versioning logic ([#ad0a8ed](https://github.com/edgexfoundry/device-rest-go/commits/ad0a8ed))
### Code Refactoring ♻
- Upgrade SDK to v1.2.4-dev.34 ([#54](https://github.com/edgexfoundry/device-rest-go/issues/54)) ([#4f6fe4f](https://github.com/edgexfoundry/device-rest-go/commits/4f6fe4f))
- update dockerfile to appropriately use ENTRYPOINT and CMD, closes[#34](https://github.com/edgexfoundry/device-rest-go/issues/34) ([#46301eb](https://github.com/edgexfoundry/device-rest-go/commits/46301eb))
### Build 👷
- upgrade device-sdk-go ([#42](https://github.com/edgexfoundry/device-rest-go/issues/42)) ([#0a79c20](https://github.com/edgexfoundry/device-rest-go/commits/0a79c20))
- Upgrade to Go1.15 ([#069cb69](https://github.com/edgexfoundry/device-rest-go/commits/069cb69))
- **all:** Enable use of DependaBot to maintain Go dependencies ([#755b338](https://github.com/edgexfoundry/device-rest-go/commits/755b338))
- **deps:** Bump github.com/edgexfoundry/device-sdk-go ([#5430346](https://github.com/edgexfoundry/device-rest-go/commits/5430346))
- **deps:** Bump github.com/spf13/cast from 1.3.0 to 1.3.1 ([#72307df](https://github.com/edgexfoundry/device-rest-go/commits/72307df))

<a name="v1.1.2"></a>
## [v1.1.2] - 2020-08-19
### Features ✨
- **device-rest:** Add snap directory for device-rest ([#6a789b2](https://github.com/edgexfoundry/device-rest-go/commits/6a789b2))
### Documentation 📖
- Add standard PR template ([#d097784](https://github.com/edgexfoundry/device-rest-go/commits/d097784))

<a name="v1.1.1"></a>
## [v1.1.1] - 2020-06-15
### Bug Fixes 🐛
- Update package name in main.go to match the one in version.go ([#fb37ef4](https://github.com/edgexfoundry/device-rest-go/commits/fb37ef4))

<a name="v1.1.0"></a>
## [v1.1.0] - 2020-05-13
### Code Refactoring ♻
- Set default logging level to INFO ([#d5d9203](https://github.com/edgexfoundry/device-rest-go/commits/d5d9203))
- upgrade SDK to v1.2.0 ([#32a9f9d](https://github.com/edgexfoundry/device-rest-go/commits/32a9f9d))
### Build 👷
- Switch to Go 1.13 ([#2cc5958](https://github.com/edgexfoundry/device-rest-go/commits/2cc5958))

<a name="v1.0.0"></a>
## v1.0.0 - 2020-02-18
### Features ✨
- **rest ds:** Implement new REST Device service ([#5c6b288](https://github.com/edgexfoundry/device-rest-go/commits/5c6b288))
### Bug Fixes 🐛
- Update to latest release of SDK V1.1.2 for mediaType fix ([#49bf546](https://github.com/edgexfoundry/device-rest-go/commits/49bf546))

[Unreleased]: https://github.com/edgexfoundry/device-rest-go/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/device-rest-go/compare/v1.2.1...x.y.z
[v1.2.1]: https://github.com/edgexfoundry/device-rest-go/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/edgexfoundry/device-rest-go/compare/v1.1.2...v1.2.0
[v1.1.2]: https://github.com/edgexfoundry/device-rest-go/compare/v1.1.1...v1.1.2
[v1.1.1]: https://github.com/edgexfoundry/device-rest-go/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/edgexfoundry/device-rest-go/compare/v1.0.0...v1.1.0
