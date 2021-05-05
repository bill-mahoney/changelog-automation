
<a name="x.y.z"></a>
## [x.y.z] - 2021-04-19
### Features ✨
- Add Registry/Config Access token capability ([#182](https://github.com/edgexfoundry/device-virtual-go/issues/182)) ([#ade1702](https://github.com/edgexfoundry/device-virtual-go/commits/ade1702))
    ```
    BREAKING CHANGE:
    When run with the secure Edgex Stack now need to have the SecretStore configured, a Vault token created and run with EDGEX_SECURITY_SECRET_STORE=true.
    ```
- update driver implementation to reflect v2 profiles ([#0759054](https://github.com/edgexfoundry/device-virtual-go/commits/0759054))
- Remove Logging configuration ([#7c0b286](https://github.com/edgexfoundry/device-virtual-go/commits/7c0b286))
### Bug Fixes 🐛
- pass correct argument in prepareVirtualResources ([#3f1af1c](https://github.com/edgexfoundry/device-virtual-go/commits/3f1af1c))
### Code Refactoring ♻
- consume v2 Device SDK ([#941086c](https://github.com/edgexfoundry/device-virtual-go/commits/941086c))
### Documentation 📖
- Add badges to readme ([#e3e4674](https://github.com/edgexfoundry/device-virtual-go/commits/e3e4674))
### Build 👷
- Bump device sdk version ([#26239a8](https://github.com/edgexfoundry/device-virtual-go/commits/26239a8))
- upgrade SDK version ([#2e7a8e4](https://github.com/edgexfoundry/device-virtual-go/commits/2e7a8e4))
- bump SDK version ([#74fd182](https://github.com/edgexfoundry/device-virtual-go/commits/74fd182))
- **deps:** Bump github.com/edgexfoundry/device-sdk-go/v2 ([#5b10962](https://github.com/edgexfoundry/device-virtual-go/commits/5b10962))
- **deps:** Bump github.com/edgexfoundry/device-sdk-go/v2 ([#e1a630d](https://github.com/edgexfoundry/device-virtual-go/commits/e1a630d))

<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-02
### Code Refactoring ♻
- Upgrade SDK to v1.4.0 ([#dd6dddd](https://github.com/edgexfoundry/device-virtual-go/commits/dd6dddd))
### Build 👷
- update device-sdk-go to v1.3.1-dev.4 ([#d2603f8](https://github.com/edgexfoundry/device-virtual-go/commits/d2603f8))
- **deps:** Bump github.com/edgexfoundry/device-sdk-go ([#fb417ca](https://github.com/edgexfoundry/device-virtual-go/commits/fb417ca))
### Continuous Integration 🔄
- add semantic.yml for commit linting, update PR template to latest ([#c0dc29d](https://github.com/edgexfoundry/device-virtual-go/commits/c0dc29d))
- standardize dockerfiles ([#6351328](https://github.com/edgexfoundry/device-virtual-go/commits/6351328))

<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-18
### Features ✨
- Support array value type ([#56f7dc2](https://github.com/edgexfoundry/device-virtual-go/commits/56f7dc2))
### Doc
- Update top-level README ([#d268b7b](https://github.com/edgexfoundry/device-virtual-go/commits/d268b7b))
### Bug Fixes 🐛
- ReadWrite field of each device resource should be RW ([#b91c50e](https://github.com/edgexfoundry/device-virtual-go/commits/b91c50e))
### Code Refactoring ♻
- Upgrade SDK to v1.2.4-dev.34 ([#1077bc0](https://github.com/edgexfoundry/device-virtual-go/commits/1077bc0))
- update dockerfile to appropriately use ENTRYPOINT and CMD, closes[#125](https://github.com/edgexfoundry/device-virtual-go/issues/125) ([#ee911db](https://github.com/edgexfoundry/device-virtual-go/commits/ee911db))
### Build 👷
- update go-mod-core-contracts to 0.1.111 ([#7fc4ffb](https://github.com/edgexfoundry/device-virtual-go/commits/7fc4ffb))
- update device-sdk-go to 1.3.0 ([#b61769c](https://github.com/edgexfoundry/device-virtual-go/commits/b61769c))
- upgrade device-sdk-go ([#edf0204](https://github.com/edgexfoundry/device-virtual-go/commits/edf0204))
- upgrade to use Go1.15 ([#7a8becd](https://github.com/edgexfoundry/device-virtual-go/commits/7a8becd))
- **all:** Enable use of DependaBot to maintain Go dependencies ([#befc574](https://github.com/edgexfoundry/device-virtual-go/commits/befc574))

<a name="v1.2.3"></a>
## [v1.2.3] - 2020-08-19
### Bug Fixes 🐛
- service fails when run with read-only root file system ([#9874cd4](https://github.com/edgexfoundry/device-virtual-go/commits/9874cd4))

<a name="v1.2.2"></a>
## [v1.2.2] - 2020-07-09
### Doc
- update pr template to include dependencies section ([#e9454c0](https://github.com/edgexfoundry/device-virtual-go/commits/e9454c0))
### Bug Fixes 🐛
- High memory usage ([#02e176c](https://github.com/edgexfoundry/device-virtual-go/commits/02e176c))

<a name="v1.2.1"></a>
## [v1.2.1] - 2020-06-12
### Code Refactoring ♻
- remove binary autoevent ([#4f04737](https://github.com/edgexfoundry/device-virtual-go/commits/4f04737))
- upgrade SDK to v1.2.0 ([#01be24e](https://github.com/edgexfoundry/device-virtual-go/commits/01be24e))

<a name="v1.1.1"></a>
## [v1.1.1] - 2019-12-13

<a name="v1.1.0"></a>
## [v1.1.0] - 2019-11-18

<a name="v1.0.0"></a>
## v1.0.0 - 2019-06-26

[Unreleased]: https://github.com/edgexfoundry/device-virtual-go/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.2.3...v1.3.0
[v1.2.3]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.2.2...v1.2.3
[v1.2.2]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.2.1...v1.2.2
[v1.2.1]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.1.1...v1.2.1
[v1.1.1]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/edgexfoundry/device-virtual-go/compare/v1.0.0...v1.1.0
