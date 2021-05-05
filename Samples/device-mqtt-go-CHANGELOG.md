
<a name="x.y.z"></a>
## [x.y.z] - 2021-04-30
### Features ✨
- Remove Logging configuration ([#f1a7c6f](https://github.com/edgexfoundry/device-mqtt-go/commits/f1a7c6f))
- Fixup for PR review. ([#52941ff](https://github.com/edgexfoundry/device-mqtt-go/commits/52941ff))
- Updated Dockerfile to install dumb-init ([#bc66537](https://github.com/edgexfoundry/device-mqtt-go/commits/bc66537))
- Enable use of secret via SecretProvider for MQTT broker credentials ([#33a7955](https://github.com/edgexfoundry/device-mqtt-go/commits/33a7955))
### Bug Fixes 🐛
- Add Type='vault' to [SecretStore] config ([#7c58968](https://github.com/edgexfoundry/device-mqtt-go/commits/7c58968))
### Code Refactoring ♻
- use v2 device-sdk ([#5a126a9](https://github.com/edgexfoundry/device-mqtt-go/commits/5a126a9))
### Documentation 📖
- Add badges to readme ([#cfb712f](https://github.com/edgexfoundry/device-mqtt-go/commits/cfb712f))
### Build 👷
- update build files for zmq dependency ([#d53328a](https://github.com/edgexfoundry/device-mqtt-go/commits/d53328a))
- Upgrade paho.mqtt.golang to v1.3.1 ([#242b994](https://github.com/edgexfoundry/device-mqtt-go/commits/242b994))
- **deps:** bump github.com/edgexfoundry/device-sdk-go/v2 ([#982abba](https://github.com/edgexfoundry/device-mqtt-go/commits/982abba))
- **deps:** bump github.com/edgexfoundry/device-sdk-go/v2 ([#a9a879d](https://github.com/edgexfoundry/device-mqtt-go/commits/a9a879d))
- **deps:** bump github.com/stretchr/testify from 1.5.1 to 1.7.0 ([#5dc0bc9](https://github.com/edgexfoundry/device-mqtt-go/commits/5dc0bc9))

<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-02
### Features ✨
- **snap:** add startup-duration and startup-interval configure options ([#bad7e1b](https://github.com/edgexfoundry/device-mqtt-go/commits/bad7e1b))
### Build 👷
- **deps:** bump github.com/edgexfoundry/device-sdk-go ([#a154119](https://github.com/edgexfoundry/device-mqtt-go/commits/a154119))
### Continuous Integration 🔄
- add semantic.yml for commit linting, update PR template to latest ([#692e0b5](https://github.com/edgexfoundry/device-mqtt-go/commits/692e0b5))
- standardize dockerfiles ([#43e9764](https://github.com/edgexfoundry/device-mqtt-go/commits/43e9764))

<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-18
### Bug Fixes 🐛
- Return error instead of the panic if required config not found ([#8630507](https://github.com/edgexfoundry/device-mqtt-go/commits/8630507))
- Modify float value checking condition ([#2a661a3](https://github.com/edgexfoundry/device-mqtt-go/commits/2a661a3))
- local snap development ([#8bc9dbb](https://github.com/edgexfoundry/device-mqtt-go/commits/8bc9dbb))
### Code Refactoring ♻
- Upgrade SDK to v1.2.4-dev.34 ([#fe9eb72](https://github.com/edgexfoundry/device-mqtt-go/commits/fe9eb72))
- update dockerfile to appropriately use ENTRYPOINT and CMD, closes[#164](https://github.com/edgexfoundry/device-mqtt-go/issues/164) ([#d7447a9](https://github.com/edgexfoundry/device-mqtt-go/commits/d7447a9))
### Build 👷
- Upgrade to Go1.15 ([#b7208c3](https://github.com/edgexfoundry/device-mqtt-go/commits/b7208c3))
- add dependabot.yml ([#730afc1](https://github.com/edgexfoundry/device-mqtt-go/commits/730afc1))
- **deps:** bump github.com/edgexfoundry/device-sdk-go ([#61125b8](https://github.com/edgexfoundry/device-mqtt-go/commits/61125b8))

<a name="v1.2.2"></a>
## [v1.2.2] - 2020-08-19
### Snap
- add env override for ProfilesDir ([#48947cc](https://github.com/edgexfoundry/device-mqtt-go/commits/48947cc))
### Bug Fixes 🐛
- Optimize MQTT client creation for async value Add conn retry mechanism and use os.Exit(1) instead of the panic error ([#7f88040](https://github.com/edgexfoundry/device-mqtt-go/commits/7f88040))
### Code Refactoring ♻
- upgrade SDK to v1.2.0 ([#863c2d0](https://github.com/edgexfoundry/device-mqtt-go/commits/863c2d0))
### Documentation 📖
- Add standard PR template ([#50e33cb](https://github.com/edgexfoundry/device-mqtt-go/commits/50e33cb))

<a name="v1.1.1"></a>
## [v1.1.1] - 2019-12-13

<a name="v1.1.0"></a>
## [v1.1.0] - 2019-11-18

<a name="v1.0.0"></a>
## [v1.0.0] - 2019-06-26
### VERSION
- update to 1.0.0 ([#29bc80a](https://github.com/edgexfoundry/device-mqtt-go/commits/29bc80a))

<a name="0.7.1"></a>
## 0.7.1 - 2018-12-10

[Unreleased]: https://github.com/edgexfoundry/device-mqtt-go/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.2.2...v1.3.0
[v1.2.2]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.1.1...v1.2.2
[v1.1.1]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/edgexfoundry/device-mqtt-go/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/edgexfoundry/device-mqtt-go/compare/0.7.1...v1.0.0
