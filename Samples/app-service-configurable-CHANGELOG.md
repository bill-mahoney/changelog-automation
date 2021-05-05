
<a name="x.y.z"></a>
## [x.y.z] - 2021-04-29
### Features ✨
- Switch to Redis as the default MessageBus ([#242](https://github.com/edgexfoundry/app-service-configurable/issues/242)) ([#3684568](https://github.com/edgexfoundry/app-service-configurable/commits/3684568))
    ```
    BREAKING CHANGE:
    All services sending Events must now be configured to use Redis as the MessageBus
    ```
    ```
    BREAKING CHANGE:
    rules-engine-redis profiles has been removed.
    ```
- Add Registry/Config Access token capability via Secret Provider ([#229](https://github.com/edgexfoundry/app-service-configurable/issues/229)) ([#7b79720](https://github.com/edgexfoundry/app-service-configurable/commits/7b79720))
    ```
    BREAKING CHANGE:
    When run with the secure Edgex Stack now need to have the SecretStore configured, a Vault token created and run with EDGEX_SECURITY_SECRET_STORE=true.
    ```
    ```
    BREAKING CHANGE:
    Service key changed to `app-<profile name>`
    ```
- Enable Registry and Config Access Token ([#224](https://github.com/edgexfoundry/app-service-configurable/issues/224)) ([#4992cc8](https://github.com/edgexfoundry/app-service-configurable/commits/4992cc8))
- Add FilterBySourceName to profiles ([#211](https://github.com/edgexfoundry/app-service-configurable/issues/211)) ([#02c1bdd](https://github.com/edgexfoundry/app-service-configurable/commits/02c1bdd))
- Update profiles for latest SDK changes ([#196](https://github.com/edgexfoundry/app-service-configurable/issues/196)) ([#50a23fb](https://github.com/edgexfoundry/app-service-configurable/commits/50a23fb))
    ```
    BREAKING CHANGE:
    requires SecretStore.Type be set to `vault`
    
    * refactor: Updated Attribution.txt for new dependencies
    ```
- Added secrets configuration parameters to EncryptWithAES ([#193](https://github.com/edgexfoundry/app-service-configurable/issues/193)) ([#0f5331e](https://github.com/edgexfoundry/app-service-configurable/commits/0f5331e))
- Update profiles for new filter enhancements ([#187](https://github.com/edgexfoundry/app-service-configurable/issues/187)) ([#8e9141f](https://github.com/edgexfoundry/app-service-configurable/commits/8e9141f))
- Update profiles for new subsribe topic for V2 DTOs ([#175](https://github.com/edgexfoundry/app-service-configurable/issues/175)) ([#b2b5516](https://github.com/edgexfoundry/app-service-configurable/commits/b2b5516))
- Remove Mongo module from Attribution.txt ([#149](https://github.com/edgexfoundry/app-service-configurable/issues/149)) ([#4516a35](https://github.com/edgexfoundry/app-service-configurable/commits/4516a35))
- Allow for multiple MessageBus subscriptions ([#164](https://github.com/edgexfoundry/app-service-configurable/issues/164)) ([#2d8b7de](https://github.com/edgexfoundry/app-service-configurable/commits/2d8b7de))
- Remove MarkAsPushed feature ([#159](https://github.com/edgexfoundry/app-service-configurable/issues/159)) ([#ed155f3](https://github.com/edgexfoundry/app-service-configurable/commits/ed155f3))
- update configuration files to set default non-TLS ([#157](https://github.com/edgexfoundry/app-service-configurable/issues/157)) ([#0b6ac86](https://github.com/edgexfoundry/app-service-configurable/commits/0b6ac86))
- Remove remote logging capability ([#143](https://github.com/edgexfoundry/app-service-configurable/issues/143)) ([#dc1b719](https://github.com/edgexfoundry/app-service-configurable/commits/dc1b719))
- **security:** Add dumb-init to Dockerfile of ASC ([#168](https://github.com/edgexfoundry/app-service-configurable/issues/168)) ([#4eb982c](https://github.com/edgexfoundry/app-service-configurable/commits/4eb982c))
### Bug Fixes 🐛
- Add missing Database config to message-bus-redis profile ([#238](https://github.com/edgexfoundry/app-service-configurable/issues/238)) ([#85f2bab](https://github.com/edgexfoundry/app-service-configurable/commits/85f2bab))
- All pipeline functions require 1 or more parameters in configuration ([#162](https://github.com/edgexfoundry/app-service-configurable/issues/162)) ([#618621a](https://github.com/edgexfoundry/app-service-configurable/commits/618621a))
- **snap:** fix README's security-secret-store doc ([#207](https://github.com/edgexfoundry/app-service-configurable/issues/207)) ([#a4c663a](https://github.com/edgexfoundry/app-service-configurable/commits/a4c663a))
- **snap:** allow disabling of secret-store via config hook ([#151](https://github.com/edgexfoundry/app-service-configurable/issues/151)) ([#8bb6462](https://github.com/edgexfoundry/app-service-configurable/commits/8bb6462))
### Code Refactoring ♻
- Remove V1 subscribe topic from profiles ([#240](https://github.com/edgexfoundry/app-service-configurable/issues/240)) ([#279c7ea](https://github.com/edgexfoundry/app-service-configurable/commits/279c7ea))
- Switch to 2.0 Consul path ([#227](https://github.com/edgexfoundry/app-service-configurable/issues/227)) ([#bbf9d34](https://github.com/edgexfoundry/app-service-configurable/commits/bbf9d34))
    ```
    BREAKING CHANGE:
    Consul configuration now under the /2.0/ path
    ```
- Updated profiles to use service keys for Client names ([#217](https://github.com/edgexfoundry/app-service-configurable/issues/217)) ([#be356fe](https://github.com/edgexfoundry/app-service-configurable/commits/be356fe))
    ```
    BREAKING CHANGE:
    Clients configuration has changed
    ```
- Rework code and profiles for refactored SDK ([#214](https://github.com/edgexfoundry/app-service-configurable/issues/214)) ([#d1338e8](https://github.com/edgexfoundry/app-service-configurable/commits/d1338e8))
- Consolidate function pipeline configuration ([#208](https://github.com/edgexfoundry/app-service-configurable/issues/208)) ([#d52bde6](https://github.com/edgexfoundry/app-service-configurable/commits/d52bde6))
- Update profiles for change in Trigger configuration ([#203](https://github.com/edgexfoundry/app-service-configurable/issues/203)) ([#ca2daa4](https://github.com/edgexfoundry/app-service-configurable/commits/ca2daa4))
- Update profiles for refactored http export with secret header ([#198](https://github.com/edgexfoundry/app-service-configurable/issues/198)) ([#6a27a6a](https://github.com/edgexfoundry/app-service-configurable/commits/6a27a6a))
    ```
    BREAKING CHANGE:
    Parameters have changed for HTTP Post/Put with SecretHeader
    ```
- Renaming blackbox-tests profile to functional-tests ([#179](https://github.com/edgexfoundry/app-service-configurable/issues/179)) ([#007494f](https://github.com/edgexfoundry/app-service-configurable/commits/007494f))
- Consume new V2 App SDK ([#166](https://github.com/edgexfoundry/app-service-configurable/issues/166)) ([#b430426](https://github.com/edgexfoundry/app-service-configurable/commits/b430426))
- Remove SecretStoreExclusive configuration ([#158](https://github.com/edgexfoundry/app-service-configurable/issues/158)) ([#45b32cc](https://github.com/edgexfoundry/app-service-configurable/commits/45b32cc))
- Remove use of deprecated MQTTSend ([#145](https://github.com/edgexfoundry/app-service-configurable/issues/145)) ([#86d88ba](https://github.com/edgexfoundry/app-service-configurable/commits/86d88ba))
- Remove obsolete docker-compose files ([#144](https://github.com/edgexfoundry/app-service-configurable/issues/144)) ([#7f47c9e](https://github.com/edgexfoundry/app-service-configurable/commits/7f47c9e))
### Documentation 📖
- Add badges to readme ([#aa00b56](https://github.com/edgexfoundry/app-service-configurable/commits/aa00b56))
### Build 👷
- Update to latest SDk and add gorilla/websocket to Attribution.txt ([#220](https://github.com/edgexfoundry/app-service-configurable/issues/220)) ([#283bdc7](https://github.com/edgexfoundry/app-service-configurable/commits/283bdc7))
- Consume latest SDK V2 Module ([#172](https://github.com/edgexfoundry/app-service-configurable/issues/172)) ([#9cb6a92](https://github.com/edgexfoundry/app-service-configurable/commits/9cb6a92))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go/v2 ([#226](https://github.com/edgexfoundry/app-service-configurable/issues/226)) ([#a65e88d](https://github.com/edgexfoundry/app-service-configurable/commits/a65e88d))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go/v2 ([#216](https://github.com/edgexfoundry/app-service-configurable/issues/216)) ([#b49824f](https://github.com/edgexfoundry/app-service-configurable/commits/b49824f))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go/v2 ([#206](https://github.com/edgexfoundry/app-service-configurable/issues/206)) ([#0069c00](https://github.com/edgexfoundry/app-service-configurable/commits/0069c00))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go/v2 ([#190](https://github.com/edgexfoundry/app-service-configurable/issues/190)) ([#a06da4a](https://github.com/edgexfoundry/app-service-configurable/commits/a06da4a))
### Continuous Integration 🔄
- standardize dockerfiles ([#160](https://github.com/edgexfoundry/app-service-configurable/issues/160)) ([#29a5207](https://github.com/edgexfoundry/app-service-configurable/commits/29a5207))

<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-08
### Bug Fixes 🐛
- Upgrade to go-mod-messaging with ZMQ fix for Hanoi ([#181](https://github.com/edgexfoundry/app-service-configurable/issues/181)) ([#e7b814b](https://github.com/edgexfoundry/app-service-configurable/commits/e7b814b))
- **snap:** allow disabling of secret-store via config hook ([#180](https://github.com/edgexfoundry/app-service-configurable/issues/180)) ([#1818c95](https://github.com/edgexfoundry/app-service-configurable/commits/1818c95))
### Build 👷
- Update to use released SDK for 1.3.1 dot release ([#184](https://github.com/edgexfoundry/app-service-configurable/issues/184)) ([#072b184](https://github.com/edgexfoundry/app-service-configurable/commits/072b184))

<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-18
### Features ✨
- Add ResponseContentType to SetOutputData ([#134](https://github.com/edgexfoundry/app-service-configurable/issues/134)) ([#958790d](https://github.com/edgexfoundry/app-service-configurable/commits/958790d))
- Add ability to use PUT method for HTTP Export in configurable pipeline ([#129](https://github.com/edgexfoundry/app-service-configurable/issues/129)) ([#36f96dc](https://github.com/edgexfoundry/app-service-configurable/commits/36f96dc))
- Add AddTags function to sample, http-export & mqtt-export profiles ([#114](https://github.com/edgexfoundry/app-service-configurable/issues/114)) ([#9362ccc](https://github.com/edgexfoundry/app-service-configurable/commits/9362ccc))
- set ServerBindAddr config item, fixes [#93](https://github.com/edgexfoundry/app-service-configurable/issues/93) ([#94](https://github.com/edgexfoundry/app-service-configurable/issues/94)) ([#8f8a21a](https://github.com/edgexfoundry/app-service-configurable/commits/8f8a21a))
- **snap:** added startup and duration interval values ([#132](https://github.com/edgexfoundry/app-service-configurable/issues/132)) ([#6aed5cd](https://github.com/edgexfoundry/app-service-configurable/commits/6aed5cd))
### Revert
- remove mongo implementation ([#99](https://github.com/edgexfoundry/app-service-configurable/issues/99)) ([#71c766d](https://github.com/edgexfoundry/app-service-configurable/commits/71c766d))
### Bug Fixes 🐛
- Enable using redis streams MessageBus in secure mode ([#127](https://github.com/edgexfoundry/app-service-configurable/issues/127)) ([#07d155c](https://github.com/edgexfoundry/app-service-configurable/commits/07d155c))
- Update to latest SDK so V2 APIs are available for TAF tests ([#112](https://github.com/edgexfoundry/app-service-configurable/issues/112)) ([#6d51720](https://github.com/edgexfoundry/app-service-configurable/commits/6d51720))
- app-functions-sdk-go backwards compatibility, fixes [#95](https://github.com/edgexfoundry/app-service-configurable/issues/95) ([#abecb38](https://github.com/edgexfoundry/app-service-configurable/commits/abecb38))
### Code Refactoring ♻
- update dockerfile to appropriately use ENTRYPOINT and CMD, closes [#102](https://github.com/edgexfoundry/app-service-configurable/issues/102) ([#104](https://github.com/edgexfoundry/app-service-configurable/issues/104)) ([#52089d7](https://github.com/edgexfoundry/app-service-configurable/commits/52089d7))
- Remove ClientMonitor setting. ([#6792fb2](https://github.com/edgexfoundry/app-service-configurable/commits/6792fb2))
### Documentation 📖
- fix of READMe heading sizes per [@lenny](:/lenny) change request ([#340aba0](https://github.com/edgexfoundry/app-service-configurable/commits/340aba0))
- Add latest PR template ([#84](https://github.com/edgexfoundry/app-service-configurable/issues/84)) ([#6ceeec9](https://github.com/edgexfoundry/app-service-configurable/commits/6ceeec9))
### Build 👷
- Switch to using Go 1.15 ([#117](https://github.com/edgexfoundry/app-service-configurable/issues/117)) ([#8582f2b](https://github.com/edgexfoundry/app-service-configurable/commits/8582f2b))
- Update to used latest SDK with content type fix ([#140](https://github.com/edgexfoundry/app-service-configurable/issues/140)) ([#ba8dc87](https://github.com/edgexfoundry/app-service-configurable/commits/ba8dc87))
- Add Attribution.txt and LICENSE file to docker image ([#85](https://github.com/edgexfoundry/app-service-configurable/issues/85)) ([#1b13e71](https://github.com/edgexfoundry/app-service-configurable/commits/1b13e71))
- Change DependaBot to run daily ([#137](https://github.com/edgexfoundry/app-service-configurable/issues/137)) ([#f32ad57](https://github.com/edgexfoundry/app-service-configurable/commits/f32ad57))
- add dependabot.yml ([#90](https://github.com/edgexfoundry/app-service-configurable/issues/90)) ([#b48d588](https://github.com/edgexfoundry/app-service-configurable/commits/b48d588))
- Updated to latest SDK with version check fix ([#101](https://github.com/edgexfoundry/app-service-configurable/issues/101)) ([#bfdbddf](https://github.com/edgexfoundry/app-service-configurable/commits/bfdbddf))
- Update to latest App SDK ([#116](https://github.com/edgexfoundry/app-service-configurable/issues/116)) ([#d76b339](https://github.com/edgexfoundry/app-service-configurable/commits/d76b339))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#141](https://github.com/edgexfoundry/app-service-configurable/issues/141)) ([#7658dde](https://github.com/edgexfoundry/app-service-configurable/commits/7658dde))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#118](https://github.com/edgexfoundry/app-service-configurable/issues/118)) ([#99aa3b5](https://github.com/edgexfoundry/app-service-configurable/commits/99aa3b5))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#121](https://github.com/edgexfoundry/app-service-configurable/issues/121)) ([#3cd660e](https://github.com/edgexfoundry/app-service-configurable/commits/3cd660e))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#103](https://github.com/edgexfoundry/app-service-configurable/issues/103)) ([#e37aa20](https://github.com/edgexfoundry/app-service-configurable/commits/e37aa20))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#122](https://github.com/edgexfoundry/app-service-configurable/issues/122)) ([#daff15d](https://github.com/edgexfoundry/app-service-configurable/commits/daff15d))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#123](https://github.com/edgexfoundry/app-service-configurable/issues/123)) ([#b6c69ff](https://github.com/edgexfoundry/app-service-configurable/commits/b6c69ff))
- **deps:** bump github.com/edgexfoundry/app-functions-sdk-go ([#138](https://github.com/edgexfoundry/app-service-configurable/issues/138)) ([#79fefee](https://github.com/edgexfoundry/app-service-configurable/commits/79fefee))
- **snap:** Update snapcraft.yaml version (1.2.0) ([#83](https://github.com/edgexfoundry/app-service-configurable/issues/83)) ([#a7f3ace](https://github.com/edgexfoundry/app-service-configurable/commits/a7f3ace))
### Other changes
- remove mongo DB implementation ([#92](https://github.com/edgexfoundry/app-service-configurable/issues/92)) ([#f9d32b0](https://github.com/edgexfoundry/app-service-configurable/commits/f9d32b0))

<a name="v1.2.0"></a>
## [v1.2.0] - 2020-06-11
### Features ✨
- upgrade to app-functions-sdk-go v1.2.0 ([#81](https://github.com/edgexfoundry/app-service-configurable/issues/81)) ([#9e5891b](https://github.com/edgexfoundry/app-service-configurable/commits/9e5891b))
- Add ability to Filter functions to reverse the logic to filter out specified names ([#78](https://github.com/edgexfoundry/app-service-configurable/issues/78)) ([#18accf3](https://github.com/edgexfoundry/app-service-configurable/commits/18accf3))
### Bug Fixes 🐛
- incorrect documentation link for snap ([#fc76386](https://github.com/edgexfoundry/app-service-configurable/commits/fc76386))
### Build 👷
- **snap:** update snapcraft ([#d0bc213](https://github.com/edgexfoundry/app-service-configurable/commits/d0bc213))
### Continuous Integration 🔄
- add semantic.yml for commit linting ([#76](https://github.com/edgexfoundry/app-service-configurable/issues/76)) ([#04d8ebe](https://github.com/edgexfoundry/app-service-configurable/commits/04d8ebe))

<a name="v1.1.0"></a>
## [v1.1.0] - 2020-05-12
### Features ✨
- Update to latest SDK for latest features and fixes and tweaks ([#72](https://github.com/edgexfoundry/app-service-configurable/issues/72)) ([#3c0b3bd](https://github.com/edgexfoundry/app-service-configurable/commits/3c0b3bd))
- Updated profiles for latest security config and to latest SDK ([#65fcb17](https://github.com/edgexfoundry/app-service-configurable/commits/65fcb17))
- Integrate new Redis Message Bus ([#e01e8a5](https://github.com/edgexfoundry/app-service-configurable/commits/e01e8a5))
- **MessageBus:** Update to lasted go-mod-messaging and create sample profile for MQTT Message Bus ([#b11e8ee](https://github.com/edgexfoundry/app-service-configurable/commits/b11e8ee))
### Refector
- Change Database to be Redis and add -cp command line to Dockerfile entrypoint ([#dc9fab4](https://github.com/edgexfoundry/app-service-configurable/commits/dc9fab4))
### Doc
- **profile:** Move default configuration to "sample" profile ([#852cbb2](https://github.com/edgexfoundry/app-service-configurable/commits/852cbb2))
### Bug Fixes 🐛
- **SecretStore:** SecretStore configuration is optional ([#1757981](https://github.com/edgexfoundry/app-service-configurable/commits/1757981))
- **configuration:** Always provide mongo credentials ([#fb01f3d](https://github.com/edgexfoundry/app-service-configurable/commits/fb01f3d))
### Build 👷
- Update to latest SDK and tweaks/add/remove profiles ([#8b89b2c](https://github.com/edgexfoundry/app-service-configurable/commits/8b89b2c))
- Update four files for Go compiler 1.13. Closes [#48](https://github.com/edgexfoundry/app-service-configurable/issues/48) ([#84e673f](https://github.com/edgexfoundry/app-service-configurable/commits/84e673f))
- **go.mod:** update sdk version for latest features ([#f0de623](https://github.com/edgexfoundry/app-service-configurable/commits/f0de623))

<a name="v1.0.0"></a>
## v1.0.0 - 2019-11-12
### Bug
- **StoreForward:** Add missing configuration for Vault Integration for DB credentials ([#4c28d98](https://github.com/edgexfoundry/app-service-configurable/commits/4c28d98))
### Snap
- update go to 1.12 ([#32c1fa2](https://github.com/edgexfoundry/app-service-configurable/commits/32c1fa2))
### Features ✨
- **PushToCore:** Add PushToCore funtcion to pipeline configurations ([#9499ac6](https://github.com/edgexfoundry/app-service-configurable/commits/9499ac6))
- **StoreForward:** Use lastet SDK and update configurations for Store & Forward ([#ad6d12d](https://github.com/edgexfoundry/app-service-configurable/commits/ad6d12d))
- **TargetType:** Document use of UseTargetTypeOfByteArray ([#e2c8787](https://github.com/edgexfoundry/app-service-configurable/commits/e2c8787))
- **TargetType:** Document use of UseTargetTypeOfByteArray ([#30b7b7c](https://github.com/edgexfoundry/app-service-configurable/commits/30b7b7c))
- **app-service-configurable:** Set ApplicationVersion & SDKVersion from build via makefile ([#35dbdda](https://github.com/edgexfoundry/app-service-configurable/commits/35dbdda))
- **app-service-configurable:** Create an Application Service which create its Pipeline from Configuration ([#d577d54](https://github.com/edgexfoundry/app-service-configurable/commits/d577d54))
- **configuration:** Update configuration intervals in TOML to duration string   Fix issue [#232](https://github.com/edgexfoundry/app-service-configurable/issues/232) . ([#e1a245a](https://github.com/edgexfoundry/app-service-configurable/commits/e1a245a))
- **environment:**  Replace docker profiles with environment variable overrides ([#6fc75f0](https://github.com/edgexfoundry/app-service-configurable/commits/6fc75f0))
- **profile:** Add environment override for profile command line argument ([#b1c7bf1](https://github.com/edgexfoundry/app-service-configurable/commits/b1c7bf1))
### Bug Fixes 🐛
- **Attribution:** Add Attribution.txt file and tests to "make test" ([#25b7dc0](https://github.com/edgexfoundry/app-service-configurable/commits/25b7dc0))
- **Profile:** Use latest SDK with Registry HasConfiguration fix ([#a400715](https://github.com/edgexfoundry/app-service-configurable/commits/a400715))
- **configuration:** There is a duplicate LogLevel key in the TOML ([#1acc82c](https://github.com/edgexfoundry/app-service-configurable/commits/1acc82c))
### Build 👷
- **docker:** Adding latest and branch tags to docker images for nexus ([#fa0a795](https://github.com/edgexfoundry/app-service-configurable/commits/fa0a795))
- **sdk:** Update SDK Verison ([#2e15ac1](https://github.com/edgexfoundry/app-service-configurable/commits/2e15ac1))

[Unreleased]: https://github.com/edgexfoundry/app-service-configurable/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/app-service-configurable/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/app-service-configurable/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/app-service-configurable/compare/v1.2.0...v1.3.0
[v1.2.0]: https://github.com/edgexfoundry/app-service-configurable/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/edgexfoundry/app-service-configurable/compare/v1.0.0...v1.1.0
