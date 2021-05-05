
<a name="x.y.z"></a>
## [x.y.z] - 2021-04-20
### Features ✨
- Add ReceivedTopic to MessageEnvelope & remove Checksum ([#192d447](https://github.com/edgexfoundry/go-mod-messaging/commits/192d447))
    ```
    BREAKING CHANGE:
    Checksum property has been removed from the MessageEnvelope
    ```
### Bug Fixes 🐛
- Use Redis Pub/Sub which supports topic scheme with wild cards ([#e3da10d](https://github.com/edgexfoundry/go-mod-messaging/commits/e3da10d))
- Resolve race condition in ZMQ impl when binding to port ([#8f0eb58](https://github.com/edgexfoundry/go-mod-messaging/commits/8f0eb58))
- Fix panic in unit tests. ([#e647ae6](https://github.com/edgexfoundry/go-mod-messaging/commits/e647ae6))
- Adjusted missing v2 in remaining paths ([#7c55cb6](https://github.com/edgexfoundry/go-mod-messaging/commits/7c55cb6))
### Code Refactoring ♻
- Addressed PR comments from Jim Wang ([#192ebb1](https://github.com/edgexfoundry/go-mod-messaging/commits/192ebb1))
- Add Done() method to MockToken for latest Paho module ([#2f6b1ab](https://github.com/edgexfoundry/go-mod-messaging/commits/2f6b1ab))
### Documentation 📖
- Add badges to readme ([#f5f8d14](https://github.com/edgexfoundry/go-mod-messaging/commits/f5f8d14))
### Build 👷
- **deps:** bump github.com/eclipse/paho.mqtt.golang ([#7aae1ae](https://github.com/edgexfoundry/go-mod-messaging/commits/7aae1ae))
- **deps:** bump github.com/pebbe/zmq4 from 1.2.5 to 1.2.7 ([#24a8bef](https://github.com/edgexfoundry/go-mod-messaging/commits/24a8bef))
- **deps:** bump github.com/pebbe/zmq4 from 1.2.2 to 1.2.5 ([#e94b662](https://github.com/edgexfoundry/go-mod-messaging/commits/e94b662))
- **deps:** bump github.com/stretchr/testify from 1.3.0 to 1.7.0 ([#7f130c5](https://github.com/edgexfoundry/go-mod-messaging/commits/7f130c5))

<a name="v0.1.31"></a>
## [v0.1.31] - 2021-01-14
### Build 👷
- Update module to be a V2 module ([#2e0cd9d](https://github.com/edgexfoundry/go-mod-messaging/commits/2e0cd9d))

<a name="v0.1.30"></a>
## [v0.1.30] - 2021-01-05
### Build 👷
- **deps:** bump github.com/pebbe/zmq4 from 1.0.0 to 1.2.2 ([#f5923fe](https://github.com/edgexfoundry/go-mod-messaging/commits/f5923fe))

<a name="v0.1.29"></a>
## [v0.1.29] - 2020-12-29
### Bug Fixes 🐛
- Add ability to re-subscribe to topics when reconnected ([#e6a09cc](https://github.com/edgexfoundry/go-mod-messaging/commits/e6a09cc))

<a name="v0.1.28"></a>
## [v0.1.28] - 2020-10-20
### Bug Fixes 🐛
- replace broken link in pull request template ([#5b895e2](https://github.com/edgexfoundry/go-mod-messaging/commits/5b895e2))

<a name="v0.1.27"></a>
## [v0.1.27] - 2020-10-19
### Bug Fixes 🐛
- Change CorrelationID key constant to match recent change in edgex-go ([#47c5376](https://github.com/edgexfoundry/go-mod-messaging/commits/47c5376))

<a name="v0.1.26"></a>
## [v0.1.26] - 2020-10-09
### Bug Fixes 🐛
- **redisstreams:** Properly set Password via reflection when found in Options ([#f0ba16a](https://github.com/edgexfoundry/go-mod-messaging/commits/f0ba16a))

<a name="v0.1.25"></a>
## [v0.1.25] - 2020-10-07
### Build 👷
- add supporting files for conventional commits ([#407c69a](https://github.com/edgexfoundry/go-mod-messaging/commits/407c69a))

<a name="v0.1.24"></a>
## [v0.1.24] - 2020-10-01
### Build 👷
- **all:** Enable use of DependaBot to maintain Go dependencies ([#3f0fefd](https://github.com/edgexfoundry/go-mod-messaging/commits/3f0fefd))

<a name="v0.1.23"></a>
## [v0.1.23] - 2020-09-17
### Bug Fixes 🐛
- Fix documentation typo in README to new semver tag is created. ([#93ae0de](https://github.com/edgexfoundry/go-mod-messaging/commits/93ae0de))

<a name="v0.1.22"></a>
## [v0.1.22] - 2020-09-15
### Build 👷
- update to go 1.15 ([#6eab632](https://github.com/edgexfoundry/go-mod-messaging/commits/6eab632))

<a name="v0.1.21"></a>
## [v0.1.21] - 2020-06-17
### Documentation 📖
- Update PR Template ([#c519f80](https://github.com/edgexfoundry/go-mod-messaging/commits/c519f80))

<a name="v0.1.20"></a>
## [v0.1.20] - 2020-05-27

<a name="v0.1.19"></a>
## [v0.1.19] - 2020-04-21

<a name="v0.1.18"></a>
## [v0.1.18] - 2020-04-15

<a name="v0.1.17"></a>
## [v0.1.17] - 2020-04-03
### Bug
- **race:** Fixed races. ([#b61e84a](https://github.com/edgexfoundry/go-mod-messaging/commits/b61e84a))

<a name="v0.1.16"></a>
## [v0.1.16] - 2020-03-06

<a name="v0.1.15"></a>
## [v0.1.15] - 2020-02-19
### Build 👷
- Update relevant files in go-mod-messaging for Go 1.13. ([#b13d2f3](https://github.com/edgexfoundry/go-mod-messaging/commits/b13d2f3))

<a name="v0.1.14"></a>
## [v0.1.14] - 2020-01-23

<a name="v0.1.13"></a>
## [v0.1.13] - 2020-01-07

<a name="v0.1.12"></a>
## [v0.1.12] - 2020-01-07

<a name="v0.1.11"></a>
## [v0.1.11] - 2019-07-18

<a name="v0.1.10"></a>
## [v0.1.10] - 2019-07-18

<a name="v0.1.9"></a>
## [v0.1.9] - 2019-07-16

<a name="v0.1.8"></a>
## [v0.1.8] - 2019-07-16

<a name="v0.1.7"></a>
## [v0.1.7] - 2019-07-16

<a name="v0.1.6"></a>
## [v0.1.6] - 2019-07-10

<a name="v0.1.5"></a>
## [v0.1.5] - 2019-07-08

<a name="v0.1.4"></a>
## [v0.1.4] - 2019-07-01

<a name="v0.1.3"></a>
## [v0.1.3] - 2019-06-27

<a name="v0.1.2"></a>
## [v0.1.2] - 2019-06-20

<a name="v0.1.1"></a>
## [v0.1.1] - 2019-06-14

<a name="v0.1.0"></a>
## [v0.1.0] - 2019-05-28

<a name="v0.0.0"></a>
## v0.0.0 - 2019-05-17

[Unreleased]: https://github.com/edgexfoundry/go-mod-messaging/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.31...x.y.z
[v0.1.31]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.30...v0.1.31
[v0.1.30]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.29...v0.1.30
[v0.1.29]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.28...v0.1.29
[v0.1.28]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.27...v0.1.28
[v0.1.27]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.26...v0.1.27
[v0.1.26]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.25...v0.1.26
[v0.1.25]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.24...v0.1.25
[v0.1.24]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.23...v0.1.24
[v0.1.23]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.22...v0.1.23
[v0.1.22]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.21...v0.1.22
[v0.1.21]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.20...v0.1.21
[v0.1.20]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.19...v0.1.20
[v0.1.19]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.18...v0.1.19
[v0.1.18]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.17...v0.1.18
[v0.1.17]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.16...v0.1.17
[v0.1.16]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.15...v0.1.16
[v0.1.15]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.14...v0.1.15
[v0.1.14]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.13...v0.1.14
[v0.1.13]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.12...v0.1.13
[v0.1.12]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.11...v0.1.12
[v0.1.11]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.10...v0.1.11
[v0.1.10]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.9...v0.1.10
[v0.1.9]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.8...v0.1.9
[v0.1.8]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.7...v0.1.8
[v0.1.7]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.6...v0.1.7
[v0.1.6]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.5...v0.1.6
[v0.1.5]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.4...v0.1.5
[v0.1.4]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.3...v0.1.4
[v0.1.3]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.2...v0.1.3
[v0.1.2]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/edgexfoundry/go-mod-messaging/compare/v0.0.0...v0.1.0
