
<a name="x.y.z"></a>
## [x.y.z] - 2021-05-05
### Features ✨
- Use SecretProvider to get Config/Registry access tokens ([#202](https://github.com/edgexfoundry/go-mod-bootstrap/issues/202)) ([#5d19aa5](https://github.com/edgexfoundry/go-mod-bootstrap/commits/5d19aa5))
- Enable use of Registry & Config client access token ([#195](https://github.com/edgexfoundry/go-mod-bootstrap/issues/195)) ([#f9d06ec](https://github.com/edgexfoundry/go-mod-bootstrap/commits/f9d06ec))
- Add overwrite capability for custom configuration ([#185](https://github.com/edgexfoundry/go-mod-bootstrap/issues/185)) ([#90b8a51](https://github.com/edgexfoundry/go-mod-bootstrap/commits/90b8a51))
- Add support for load/listen custom configuration ([#180](https://github.com/edgexfoundry/go-mod-bootstrap/issues/180)) ([#f277873](https://github.com/edgexfoundry/go-mod-bootstrap/commits/f277873))
- Add config client in DIC ([#178](https://github.com/edgexfoundry/go-mod-bootstrap/issues/178)) ([#ecde49d](https://github.com/edgexfoundry/go-mod-bootstrap/commits/ecde49d))
- **v2:** Add helper to query DIC and returns the DeviceServiceCommandClient instance ([#162](https://github.com/edgexfoundry/go-mod-bootstrap/issues/162)) ([#c087e44](https://github.com/edgexfoundry/go-mod-bootstrap/commits/c087e44))
- **v2:** Create Helper functions to retrieve client library instances through DIC ([#158](https://github.com/edgexfoundry/go-mod-bootstrap/issues/158)) ([#3d89601](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3d89601))
### Bug Fixes 🐛
- Generate mock for latest SecretProvider interface ([#206](https://github.com/edgexfoundry/go-mod-bootstrap/issues/206)) ([#359809f](https://github.com/edgexfoundry/go-mod-bootstrap/commits/359809f))
- Use /api/v2/ping for Registry healthchecks ([#196](https://github.com/edgexfoundry/go-mod-bootstrap/issues/196)) ([#7d55b1a](https://github.com/edgexfoundry/go-mod-bootstrap/commits/7d55b1a))
- Use V2 Ping for health check ([#5bb40c1](https://github.com/edgexfoundry/go-mod-bootstrap/commits/5bb40c1))
### Code Refactoring ♻
- update calling GenerateConsulToken ([#212](https://github.com/edgexfoundry/go-mod-bootstrap/issues/212)) ([#e295a6e](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e295a6e))
- Replace use of BurntSushi/toml with pelletier/go-toml ([#6c8f2b4](https://github.com/edgexfoundry/go-mod-bootstrap/commits/6c8f2b4))
- Expose ConfigVersion so services can use if needed ([#204](https://github.com/edgexfoundry/go-mod-bootstrap/issues/204)) ([#e966ad5](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e966ad5))
- Set the Config Version when creating Config Client ([#201](https://github.com/edgexfoundry/go-mod-bootstrap/issues/201)) ([#615e600](https://github.com/edgexfoundry/go-mod-bootstrap/commits/615e600))
    ```
    BREAKING CHANGE:
    Configuration in Consul now under the `/2.0/` path
    ```
- Refactor ListenForCustomConfigChanges to avoid use of channel ([#187](https://github.com/edgexfoundry/go-mod-bootstrap/issues/187)) ([#cffb2fe](https://github.com/edgexfoundry/go-mod-bootstrap/commits/cffb2fe))
- Updated go.mod for tagged go-mod-secrets and fixed unittest ([#05db8a1](https://github.com/edgexfoundry/go-mod-bootstrap/commits/05db8a1))
- Add comment for new Type setting. ([#d2e6caa](https://github.com/edgexfoundry/go-mod-bootstrap/commits/d2e6caa))
- Update to latest go-mo-secrets ([#e4bb43c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e4bb43c))
- Consume V2 Go Modules for edgex go-mods ([#155](https://github.com/edgexfoundry/go-mod-bootstrap/issues/155)) ([#ec2d1cf](https://github.com/edgexfoundry/go-mod-bootstrap/commits/ec2d1cf))
- Make module a Go V2 Module ([#149](https://github.com/edgexfoundry/go-mod-bootstrap/issues/149)) ([#b42b1bf](https://github.com/edgexfoundry/go-mod-bootstrap/commits/b42b1bf))
### Documentation 📖
- Add badges to readme ([#8e1e445](https://github.com/edgexfoundry/go-mod-bootstrap/commits/8e1e445))
### Build 👷
- Changes for latest go-mod-secrets. ([#07dd28c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/07dd28c))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#57a7a52](https://github.com/edgexfoundry/go-mod-bootstrap/commits/57a7a52))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#83d2cf2](https://github.com/edgexfoundry/go-mod-bootstrap/commits/83d2cf2))
- **deps:** bump github.com/edgexfoundry/go-mod-registry/v2 ([#90caf0d](https://github.com/edgexfoundry/go-mod-bootstrap/commits/90caf0d))
- **deps:** bump github.com/edgexfoundry/go-mod-configuration/v2 ([#b89ca1b](https://github.com/edgexfoundry/go-mod-bootstrap/commits/b89ca1b))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#539da73](https://github.com/edgexfoundry/go-mod-bootstrap/commits/539da73))
- **deps:** bump github.com/edgexfoundry/go-mod-configuration/v2 ([#759c5a1](https://github.com/edgexfoundry/go-mod-bootstrap/commits/759c5a1))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#e9074fb](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e9074fb))
- **deps:** bump github.com/pelletier/go-toml from 1.2.0 to 1.9.0 ([#207](https://github.com/edgexfoundry/go-mod-bootstrap/issues/207)) ([#63671d6](https://github.com/edgexfoundry/go-mod-bootstrap/commits/63671d6))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#e611b74](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e611b74))
- **deps:** bump github.com/edgexfoundry/go-mod-configuration/v2 ([#37a3be9](https://github.com/edgexfoundry/go-mod-bootstrap/commits/37a3be9))
- **deps:** bump github.com/edgexfoundry/go-mod-registry/v2 ([#d5c3cf8](https://github.com/edgexfoundry/go-mod-bootstrap/commits/d5c3cf8))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#d59008f](https://github.com/edgexfoundry/go-mod-bootstrap/commits/d59008f))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#3556118](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3556118))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#bd03179](https://github.com/edgexfoundry/go-mod-bootstrap/commits/bd03179))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#448bfb9](https://github.com/edgexfoundry/go-mod-bootstrap/commits/448bfb9))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#b43ff56](https://github.com/edgexfoundry/go-mod-bootstrap/commits/b43ff56))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#1a77a09](https://github.com/edgexfoundry/go-mod-bootstrap/commits/1a77a09))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#3947473](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3947473))
- **deps:** bump github.com/edgexfoundry/go-mod-registry/v2 ([#e1376da](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e1376da))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#9da8261](https://github.com/edgexfoundry/go-mod-bootstrap/commits/9da8261))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#717a705](https://github.com/edgexfoundry/go-mod-bootstrap/commits/717a705))
- **deps:** bump github.com/edgexfoundry/go-mod-configuration/v2 ([#d57abc8](https://github.com/edgexfoundry/go-mod-bootstrap/commits/d57abc8))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets/v2 ([#f8cf932](https://github.com/edgexfoundry/go-mod-bootstrap/commits/f8cf932))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#b004487](https://github.com/edgexfoundry/go-mod-bootstrap/commits/b004487))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#db21531](https://github.com/edgexfoundry/go-mod-bootstrap/commits/db21531))

<a name="v0.0.72"></a>
## [v0.0.72] - 2021-01-19
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#8e68301](https://github.com/edgexfoundry/go-mod-bootstrap/commits/8e68301))

<a name="v0.0.71"></a>
## [v0.0.71] - 2021-01-19
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#622faa5](https://github.com/edgexfoundry/go-mod-bootstrap/commits/622faa5))

<a name="v0.0.70"></a>
## [v0.0.70] - 2021-01-12
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#dfddf70](https://github.com/edgexfoundry/go-mod-bootstrap/commits/dfddf70))

<a name="v0.0.69"></a>
## [v0.0.69] - 2021-01-12
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#a9023bd](https://github.com/edgexfoundry/go-mod-bootstrap/commits/a9023bd))

<a name="v0.0.68"></a>
## [v0.0.68] - 2021-01-04
### Features ✨
- Enhance Timer to be used for timed loops beyond bootstrapping ([#141](https://github.com/edgexfoundry/go-mod-bootstrap/issues/141)) ([#ff8e38c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/ff8e38c))
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#4bc43ba](https://github.com/edgexfoundry/go-mod-bootstrap/commits/4bc43ba))

<a name="v0.0.67"></a>
## [v0.0.67] - 2021-01-04
### Bug Fixes 🐛
- Add setting the configured LogLevel ([#143](https://github.com/edgexfoundry/go-mod-bootstrap/issues/143)) ([#9cbc3d8](https://github.com/edgexfoundry/go-mod-bootstrap/commits/9cbc3d8))

<a name="v0.0.66"></a>
## [v0.0.66] - 2020-12-30
### Code Refactoring ♻
- Remove backward compatibility code ([#139](https://github.com/edgexfoundry/go-mod-bootstrap/issues/139)) ([#c10d266](https://github.com/edgexfoundry/go-mod-bootstrap/commits/c10d266))

<a name="v0.0.65"></a>
## [v0.0.65] - 2020-12-29
### Code Refactoring ♻
- Refactor to remove remote and file logging ([#138](https://github.com/edgexfoundry/go-mod-bootstrap/issues/138)) ([#d92118e](https://github.com/edgexfoundry/go-mod-bootstrap/commits/d92118e))

<a name="v0.0.64"></a>
## [v0.0.64] - 2020-12-20
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#135](https://github.com/edgexfoundry/go-mod-bootstrap/issues/135)) ([#cb3a4e9](https://github.com/edgexfoundry/go-mod-bootstrap/commits/cb3a4e9))

<a name="v0.0.63"></a>
## [v0.0.63] - 2020-12-20
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#137](https://github.com/edgexfoundry/go-mod-bootstrap/issues/137)) ([#c718a8c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/c718a8c))

<a name="v0.0.62"></a>
## [v0.0.62] - 2020-12-20
### Code Refactoring ♻
- Secret Provider for all services ([#134](https://github.com/edgexfoundry/go-mod-bootstrap/issues/134)) ([#6cb9329](https://github.com/edgexfoundry/go-mod-bootstrap/commits/6cb9329))

<a name="v0.0.61"></a>
## [v0.0.61] - 2020-11-30
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#88e4328](https://github.com/edgexfoundry/go-mod-bootstrap/commits/88e4328))

<a name="v0.0.60"></a>
## [v0.0.60] - 2020-11-25
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#df66839](https://github.com/edgexfoundry/go-mod-bootstrap/commits/df66839))

<a name="v0.0.59"></a>
## [v0.0.59] - 2020-11-25
### Bug Fixes 🐛
- LoggingClientFrom handle nil case properly ([#c95d24f](https://github.com/edgexfoundry/go-mod-bootstrap/commits/c95d24f))

<a name="v0.0.58"></a>
## [v0.0.58] - 2020-11-19
### Features ✨
- Allow service to pass in initial logging client ([#3651de7](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3651de7))
### Bug Fixes 🐛
- Fixed failing unit test ([#4f61d0f](https://github.com/edgexfoundry/go-mod-bootstrap/commits/4f61d0f))

<a name="v0.0.57"></a>
## [v0.0.57] - 2020-10-28
### Bug Fixes 🐛
- Accept argument lists with a -r substring ([#dc0e6ea](https://github.com/edgexfoundry/go-mod-bootstrap/commits/dc0e6ea))

<a name="v0.0.56"></a>
## [v0.0.56] - 2020-10-26
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#6297c6d](https://github.com/edgexfoundry/go-mod-bootstrap/commits/6297c6d))

<a name="v0.0.55"></a>
## [v0.0.55] - 2020-10-26
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#bc7c955](https://github.com/edgexfoundry/go-mod-bootstrap/commits/bc7c955))

<a name="v0.0.54"></a>
## [v0.0.54] - 2020-10-26
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-configuration ([#4068a76](https://github.com/edgexfoundry/go-mod-bootstrap/commits/4068a76))

<a name="v0.0.53"></a>
## [v0.0.53] - 2020-10-20
### Bug Fixes 🐛
- replace broken link in pull request template ([#24b73a6](https://github.com/edgexfoundry/go-mod-bootstrap/commits/24b73a6))

<a name="v0.0.52"></a>
## [v0.0.52] - 2020-10-20
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#2be03d2](https://github.com/edgexfoundry/go-mod-bootstrap/commits/2be03d2))

<a name="v0.0.51"></a>
## [v0.0.51] - 2020-10-20
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#e140222](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e140222))

<a name="v0.0.50"></a>
## [v0.0.50] - 2020-10-14
### Bug Fixes 🐛
- Handle env override values which have the '=' character ([#4846fb7](https://github.com/edgexfoundry/go-mod-bootstrap/commits/4846fb7))

<a name="v0.0.49"></a>
## [v0.0.49] - 2020-10-13
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#454d218](https://github.com/edgexfoundry/go-mod-bootstrap/commits/454d218))
- **deps:** bump github.com/edgexfoundry/go-mod-configuration ([#eb8a065](https://github.com/edgexfoundry/go-mod-bootstrap/commits/eb8a065))

<a name="v0.0.48"></a>
## [v0.0.48] - 2020-10-13
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#2df6b6c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/2df6b6c))

<a name="v0.0.47"></a>
## [v0.0.47] - 2020-10-07
### Build 👷
- add supporting files for conventional commits ([#79767ce](https://github.com/edgexfoundry/go-mod-bootstrap/commits/79767ce))

<a name="v0.0.46"></a>
## [v0.0.46] - 2020-10-05
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#57fcc74](https://github.com/edgexfoundry/go-mod-bootstrap/commits/57fcc74))

<a name="v0.0.45"></a>
## [v0.0.45] - 2020-10-05
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#face20a](https://github.com/edgexfoundry/go-mod-bootstrap/commits/face20a))

<a name="v0.0.44"></a>
## [v0.0.44] - 2020-10-05
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-configuration ([#e324f7c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e324f7c))

<a name="v0.0.43"></a>
## [v0.0.43] - 2020-10-01
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#54fdde4](https://github.com/edgexfoundry/go-mod-bootstrap/commits/54fdde4))

<a name="v0.0.42"></a>
## [v0.0.42] - 2020-10-01
### Build 👷
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#1bd7bf4](https://github.com/edgexfoundry/go-mod-bootstrap/commits/1bd7bf4))

<a name="v0.0.41"></a>
## [v0.0.41] - 2020-09-29
### Bug Fixes 🐛
- Increase default startup duration to 60 seconds ([#0761e33](https://github.com/edgexfoundry/go-mod-bootstrap/commits/0761e33))

<a name="v0.0.40"></a>
## [v0.0.40] - 2020-09-24
### Build 👷
- **all:** Enable use of DependaBot to maintain Go dependencies ([#3a76aab](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3a76aab))

<a name="v0.0.39"></a>
## [v0.0.39] - 2020-09-16
### Build 👷
- Update dependent go-mod versions ([#155451e](https://github.com/edgexfoundry/go-mod-bootstrap/commits/155451e))

<a name="v0.0.38"></a>
## [v0.0.38] - 2020-09-11
### Bug Fixes 🐛
- **build:** update to go 1.15 ([#090288d](https://github.com/edgexfoundry/go-mod-bootstrap/commits/090288d))

<a name="v0.0.37"></a>
## [v0.0.37] - 2020-07-30
### Bug Fixes 🐛
- Startup Duration and Interval never updated from default values ([#c35f13c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/c35f13c))

<a name="v0.0.36"></a>
## [v0.0.36] - 2020-07-13
### Bug Fixes 🐛
- configurable ip address for ListenAndServe, fixes [#83](https://github.com/edgexfoundry/go-mod-bootstrap/issues/83) ([#ec63238](https://github.com/edgexfoundry/go-mod-bootstrap/commits/ec63238))

<a name="v0.0.35"></a>
## [v0.0.35] - 2020-07-07
### Code Refactoring ♻
- **config:** Remove ClientMonitor from the ServiceInfo struct ([#efe9cb9](https://github.com/edgexfoundry/go-mod-bootstrap/commits/efe9cb9))

<a name="v0.0.34"></a>
## [v0.0.34] - 2020-06-17
### Documentation 📖
- Update PR Template ([#bc6754a](https://github.com/edgexfoundry/go-mod-bootstrap/commits/bc6754a))

<a name="v0.0.33"></a>
## [v0.0.33] - 2020-06-01
### Bug Fixes 🐛
- Chnaged from using blank hostname to 0.0.0.0 ([#38f87ec](https://github.com/edgexfoundry/go-mod-bootstrap/commits/38f87ec))
- Don't use hostname for webserver ListenAndServe ([#6dbe24f](https://github.com/edgexfoundry/go-mod-bootstrap/commits/6dbe24f))

<a name="v0.0.32"></a>
## [v0.0.32] - 2020-05-29
### Bug Fixes 🐛
- Allow overrides that have empty/blank value ([#5497010](https://github.com/edgexfoundry/go-mod-bootstrap/commits/5497010))

<a name="v0.0.31"></a>
## [v0.0.31] - 2020-04-29
### Bug Fixes 🐛
- **config:** Ignore first config changes notification on start-up ([#2834834](https://github.com/edgexfoundry/go-mod-bootstrap/commits/2834834))

<a name="v0.0.30"></a>
## [v0.0.30] - 2020-04-21
### Features ✨
- **environment:** Perform case insensitive comparision for override names ([#3d7becb](https://github.com/edgexfoundry/go-mod-bootstrap/commits/3d7becb))

<a name="v0.0.29"></a>
## [v0.0.29] - 2020-04-16

<a name="v0.0.28"></a>
## [v0.0.28] - 2020-04-14
### Bug Fixes 🐛
- **config:** Change UpdatedStream to be defined as `chan struct{}` ([#6d2e43b](https://github.com/edgexfoundry/go-mod-bootstrap/commits/6d2e43b))

<a name="v0.0.27"></a>
## [v0.0.27] - 2020-04-10

<a name="v0.0.26"></a>
## [v0.0.26] - 2020-03-31
### Bug Fixes 🐛
- **logging:** Logger not configured properly ([#017c944](https://github.com/edgexfoundry/go-mod-bootstrap/commits/017c944))

<a name="v0.0.25"></a>
## [v0.0.25] - 2020-03-30
### Features ✨
- Add Self seeding, env var overrides, cmd-line options per ADR 0005-Service-Self-Config.md ([#59](https://github.com/edgexfoundry/go-mod-bootstrap/issues/59)) ([#e56334c](https://github.com/edgexfoundry/go-mod-bootstrap/commits/e56334c))

<a name="v0.0.24"></a>
## [v0.0.24] - 2020-03-26
### Bug Fixes 🐛
- Add retry loop for secret client if initial token is invalid ([#60](https://github.com/edgexfoundry/go-mod-bootstrap/issues/60)) ([#ecac4d1](https://github.com/edgexfoundry/go-mod-bootstrap/commits/ecac4d1))

<a name="v0.0.23"></a>
## [v0.0.23] - 2020-03-23

<a name="v0.0.22"></a>
## [v0.0.22] - 2020-03-18

<a name="v0.0.21"></a>
## [v0.0.21] - 2020-02-24

<a name="v0.0.20"></a>
## [v0.0.20] - 2020-02-18

<a name="v0.0.19"></a>
## [v0.0.19] - 2020-02-11

<a name="v0.0.18"></a>
## [v0.0.18] - 2020-02-11

<a name="v0.0.17"></a>
## [v0.0.17] - 2020-02-10

<a name="v0.0.16"></a>
## [v0.0.16] - 2020-02-10
### Build 👷
- Update relevant files in go-mod-bootstrap for Go 1.13. ([#48](https://github.com/edgexfoundry/go-mod-bootstrap/issues/48)) ([#1355dd1](https://github.com/edgexfoundry/go-mod-bootstrap/commits/1355dd1))

<a name="v0.0.15"></a>
## [v0.0.15] - 2020-02-07

<a name="v0.0.14"></a>
## [v0.0.14] - 2020-02-06

<a name="v0.0.13"></a>
## [v0.0.13] - 2020-02-04
### Bug
- **config:** Embedded types do not work with package we use to pull from Consul ([#38](https://github.com/edgexfoundry/go-mod-bootstrap/issues/38)) ([#2d9fcd4](https://github.com/edgexfoundry/go-mod-bootstrap/commits/2d9fcd4))

<a name="v0.0.12"></a>
## [v0.0.12] - 2020-01-31
### Code Refactoring ♻
- **registry:** Integrate new Configuration & Registry clients ([#915c058](https://github.com/edgexfoundry/go-mod-bootstrap/commits/915c058))

<a name="v0.0.11"></a>
## [v0.0.11] - 2020-01-16

<a name="v0.0.10"></a>
## [v0.0.10] - 2020-01-16

<a name="v0.0.9"></a>
## [v0.0.9] - 2020-01-15

<a name="v0.0.8"></a>
## [v0.0.8] - 2020-01-10

<a name="v0.0.7"></a>
## [v0.0.7] - 2020-01-07

<a name="v0.0.6"></a>
## [v0.0.6] - 2020-01-07

<a name="v0.0.5"></a>
## [v0.0.5] - 2020-01-07

<a name="v0.0.4"></a>
## [v0.0.4] - 2020-01-07

<a name="v0.0.3"></a>
## [v0.0.3] - 2019-12-30

<a name="v0.0.2"></a>
## [v0.0.2] - 2019-12-28

<a name="v0.0.1"></a>
## v0.0.1 - 2019-12-18

[Unreleased]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.72...x.y.z
[v0.0.72]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.71...v0.0.72
[v0.0.71]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.70...v0.0.71
[v0.0.70]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.69...v0.0.70
[v0.0.69]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.68...v0.0.69
[v0.0.68]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.67...v0.0.68
[v0.0.67]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.66...v0.0.67
[v0.0.66]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.65...v0.0.66
[v0.0.65]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.64...v0.0.65
[v0.0.64]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.63...v0.0.64
[v0.0.63]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.62...v0.0.63
[v0.0.62]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.61...v0.0.62
[v0.0.61]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.60...v0.0.61
[v0.0.60]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.59...v0.0.60
[v0.0.59]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.58...v0.0.59
[v0.0.58]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.57...v0.0.58
[v0.0.57]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.56...v0.0.57
[v0.0.56]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.55...v0.0.56
[v0.0.55]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.54...v0.0.55
[v0.0.54]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.53...v0.0.54
[v0.0.53]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.52...v0.0.53
[v0.0.52]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.51...v0.0.52
[v0.0.51]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.50...v0.0.51
[v0.0.50]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.49...v0.0.50
[v0.0.49]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.48...v0.0.49
[v0.0.48]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.47...v0.0.48
[v0.0.47]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.46...v0.0.47
[v0.0.46]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.45...v0.0.46
[v0.0.45]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.44...v0.0.45
[v0.0.44]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.43...v0.0.44
[v0.0.43]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.42...v0.0.43
[v0.0.42]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.41...v0.0.42
[v0.0.41]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.40...v0.0.41
[v0.0.40]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.39...v0.0.40
[v0.0.39]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.38...v0.0.39
[v0.0.38]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.37...v0.0.38
[v0.0.37]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.36...v0.0.37
[v0.0.36]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.35...v0.0.36
[v0.0.35]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.34...v0.0.35
[v0.0.34]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.33...v0.0.34
[v0.0.33]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.32...v0.0.33
[v0.0.32]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.31...v0.0.32
[v0.0.31]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.30...v0.0.31
[v0.0.30]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.29...v0.0.30
[v0.0.29]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.28...v0.0.29
[v0.0.28]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.27...v0.0.28
[v0.0.27]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.26...v0.0.27
[v0.0.26]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.25...v0.0.26
[v0.0.25]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.24...v0.0.25
[v0.0.24]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.23...v0.0.24
[v0.0.23]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.22...v0.0.23
[v0.0.22]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.21...v0.0.22
[v0.0.21]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.20...v0.0.21
[v0.0.20]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.19...v0.0.20
[v0.0.19]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.18...v0.0.19
[v0.0.18]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.17...v0.0.18
[v0.0.17]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.16...v0.0.17
[v0.0.16]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.15...v0.0.16
[v0.0.15]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.14...v0.0.15
[v0.0.14]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.13...v0.0.14
[v0.0.13]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.12...v0.0.13
[v0.0.12]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.11...v0.0.12
[v0.0.11]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.10...v0.0.11
[v0.0.10]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.9...v0.0.10
[v0.0.9]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.8...v0.0.9
[v0.0.8]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.7...v0.0.8
[v0.0.7]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.6...v0.0.7
[v0.0.6]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.5...v0.0.6
[v0.0.5]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.4...v0.0.5
[v0.0.4]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.3...v0.0.4
[v0.0.3]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.2...v0.0.3
[v0.0.2]: https://github.com/edgexfoundry/go-mod-bootstrap/compare/v0.0.1...v0.0.2
