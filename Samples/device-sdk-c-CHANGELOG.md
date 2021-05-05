
<a name="x.y.z"></a>
## [x.y.z] - 2021-05-04
### Features ✨
- create new devices from json files in configured directory [#331](https://github.com/edgexfoundry/device-sdk-c/issues/331) ([#336](https://github.com/edgexfoundry/device-sdk-c/issues/336)) ([#a1bd3e4](https://github.com/edgexfoundry/device-sdk-c/commits/a1bd3e4))
- Use v2 REST API, remove v1 implementations ([#324](https://github.com/edgexfoundry/device-sdk-c/issues/324)) ([#8c8f643](https://github.com/edgexfoundry/device-sdk-c/commits/8c8f643))
### Bug Fixes 🐛
- update Service Keys to new style ([#333](https://github.com/edgexfoundry/device-sdk-c/issues/333)) ([#342](https://github.com/edgexfoundry/device-sdk-c/issues/342)) ([#0a87d40](https://github.com/edgexfoundry/device-sdk-c/commits/0a87d40))
- cmake fixes, feat: callback structure population helper ([#325](https://github.com/edgexfoundry/device-sdk-c/issues/325), [#326](https://github.com/edgexfoundry/device-sdk-c/issues/326)) ([#328](https://github.com/edgexfoundry/device-sdk-c/issues/328)) ([#603e15a](https://github.com/edgexfoundry/device-sdk-c/commits/603e15a))
- update v2 REST API with recent changes ([#323](https://github.com/edgexfoundry/device-sdk-c/issues/323)) ([#eab06a1](https://github.com/edgexfoundry/device-sdk-c/commits/eab06a1))
- remove various compatibility/legacy code ([#320](https://github.com/edgexfoundry/device-sdk-c/issues/320)) ([#6cbfd1a](https://github.com/edgexfoundry/device-sdk-c/commits/6cbfd1a))
- Use Writable section for dynamic configuration ([#313](https://github.com/edgexfoundry/device-sdk-c/issues/313)) ([#a549a37](https://github.com/edgexfoundry/device-sdk-c/commits/a549a37))
### Code Refactoring ♻
- Switch to 2.0 Consul path ([#340](https://github.com/edgexfoundry/device-sdk-c/issues/340)) ([#3a634a1](https://github.com/edgexfoundry/device-sdk-c/commits/3a634a1))
- remove remaining v1 and other redundant code ([#306](https://github.com/edgexfoundry/device-sdk-c/issues/306)) ([#327](https://github.com/edgexfoundry/device-sdk-c/issues/327)) ([#77b44f9](https://github.com/edgexfoundry/device-sdk-c/commits/77b44f9))
### Documentation 📖
- Add badges to readme ([#ffca8a7](https://github.com/edgexfoundry/device-sdk-c/commits/ffca8a7))

<a name="v1.3.1"></a>
## [v1.3.1] - 2021-01-22
### Bug Fixes 🐛
- block device operations when service is locked ([#319](https://github.com/edgexfoundry/device-sdk-c/issues/319)) ([#e144b80](https://github.com/edgexfoundry/device-sdk-c/commits/e144b80))
### Continuous Integration 🔄
- standardize dockerfiles ([#317](https://github.com/edgexfoundry/device-sdk-c/issues/317)) ([#f0de00c](https://github.com/edgexfoundry/device-sdk-c/commits/f0de00c))
- add semantic.yml for commit linting ([#302](https://github.com/edgexfoundry/device-sdk-c/issues/302)) ([#706af55](https://github.com/edgexfoundry/device-sdk-c/commits/706af55))

<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-11
### Features ✨
- REST v2 Device Service endpoints ([#257](https://github.com/edgexfoundry/device-sdk-c/issues/257)) ([#299](https://github.com/edgexfoundry/device-sdk-c/issues/299)) ([#ac2ba39](https://github.com/edgexfoundry/device-sdk-c/commits/ac2ba39))
- add v2 metrics endpoint ([#298](https://github.com/edgexfoundry/device-sdk-c/issues/298)) ([#0d340e7](https://github.com/edgexfoundry/device-sdk-c/commits/0d340e7))
- implement minimum/maximum limits for write ops ([#211](https://github.com/edgexfoundry/device-sdk-c/issues/211)) ([#ea19db6](https://github.com/edgexfoundry/device-sdk-c/commits/ea19db6))
- process CBOR payloads in device PUT ([#289](https://github.com/edgexfoundry/device-sdk-c/issues/289)) ([#869b6dd](https://github.com/edgexfoundry/device-sdk-c/commits/869b6dd))
- Add ServerBindAddr config to set which interface to listen on ([#278](https://github.com/edgexfoundry/device-sdk-c/issues/278)) ([#08585c6](https://github.com/edgexfoundry/device-sdk-c/commits/08585c6))
- Implement mask operation for PUTs. Add example illustrating mask/shift usage. ([#4871229](https://github.com/edgexfoundry/device-sdk-c/commits/4871229))
- implement device endpoint for v2 REST API ([#433f8bd](https://github.com/edgexfoundry/device-sdk-c/commits/433f8bd))
- implement config endpoint for v2 REST API ([#e822fbe](https://github.com/edgexfoundry/device-sdk-c/commits/e822fbe))
- Move to Alpine version 3.11 ([#9a1a9a8](https://github.com/edgexfoundry/device-sdk-c/commits/9a1a9a8))
- Add devsdk_get_device / devsdk_get_devices - returns (list of) devices with protocol addresses and resource   information but without additional device and profile metadata ([#504bdd1](https://github.com/edgexfoundry/device-sdk-c/commits/504bdd1))
- Serialiaze events for transmission to core-data with configurable queue length ([#51dde0c](https://github.com/edgexfoundry/device-sdk-c/commits/51dde0c))
### Refac
- update Event/Reading model information ([#292](https://github.com/edgexfoundry/device-sdk-c/issues/292)) ([#3489f0f](https://github.com/edgexfoundry/device-sdk-c/commits/3489f0f))
- reorder shutdown sequence ([#284](https://github.com/edgexfoundry/device-sdk-c/issues/284)) ([#9ac00a8](https://github.com/edgexfoundry/device-sdk-c/commits/9ac00a8))
- correct calloc usage, remove stray assignment in url processor ([#66c4c88](https://github.com/edgexfoundry/device-sdk-c/commits/66c4c88))
### Bug
- don't ask for support-logging unless we need it ([#1e33aae](https://github.com/edgexfoundry/device-sdk-c/commits/1e33aae))
### Doc
- add example showing devsdk_post_readings use ([#279](https://github.com/edgexfoundry/device-sdk-c/issues/279)) ([#db1d01e](https://github.com/edgexfoundry/device-sdk-c/commits/db1d01e))
- fix wrong environment variable ([#8de3bc4](https://github.com/edgexfoundry/device-sdk-c/commits/8de3bc4))
### Revert
- Reinstate remote logging capability ([#281](https://github.com/edgexfoundry/device-sdk-c/issues/281)) ([#71c18e7](https://github.com/edgexfoundry/device-sdk-c/commits/71c18e7))
### Refact
- Group http request / reply values into structs Perform parameterized URL path matching in the toplevel handler Add v2 ping endpoint in the new style ([#1cf547c](https://github.com/edgexfoundry/device-sdk-c/commits/1cf547c))
### Examples
- add signal masking code ([#dc92159](https://github.com/edgexfoundry/device-sdk-c/commits/dc92159))
- move the v2 examples to the top level. retain the v1 template example for reference but not the others. ([#0a0c9f8](https://github.com/edgexfoundry/device-sdk-c/commits/0a0c9f8))
### Bug Fixes 🐛
- remove stale profiles when devices are removed ([#301](https://github.com/edgexfoundry/device-sdk-c/issues/301)) ([#1c3cbe1](https://github.com/edgexfoundry/device-sdk-c/commits/1c3cbe1))
- Validate boolean array data ([#3c2e643](https://github.com/edgexfoundry/device-sdk-c/commits/3c2e643))
- Pin the IOT Utils version ([#295](https://github.com/edgexfoundry/device-sdk-c/issues/295)). Initialize the IOT Utils earlier so that default configs can be constructed. ([#02385d7](https://github.com/edgexfoundry/device-sdk-c/commits/02385d7))
- url-escape device names when setting opstate. Make opstate setting part of the devsdk interface. ([#251b62f](https://github.com/edgexfoundry/device-sdk-c/commits/251b62f))
- default listening interface is [Service]/Host ([#ce20d29](https://github.com/edgexfoundry/device-sdk-c/commits/ce20d29))
- validate boolean data ([#287](https://github.com/edgexfoundry/device-sdk-c/issues/287)) ([#65d0033](https://github.com/edgexfoundry/device-sdk-c/commits/65d0033))
- memleaks when metadata calls fail ([#5bd72f0](https://github.com/edgexfoundry/device-sdk-c/commits/5bd72f0))
- suppress warnings from recent gcc re json string handling remove unhelpful profile directory setting from configurations ([#10d40ff](https://github.com/edgexfoundry/device-sdk-c/commits/10d40ff))
- wrong map size for CBOR readings feat: take a reasonable default for mediaType ([#414b841](https://github.com/edgexfoundry/device-sdk-c/commits/414b841))
### Code Refactoring ♻
- Remove unimplemented config options ([#3083374](https://github.com/edgexfoundry/device-sdk-c/commits/3083374))
- Remove Logging Service support ([#274](https://github.com/edgexfoundry/device-sdk-c/issues/274)) ([#41f864f](https://github.com/edgexfoundry/device-sdk-c/commits/41f864f))
### Documentation 📖
- addition of version and LTS refs to README per arch's meeting ([#293](https://github.com/edgexfoundry/device-sdk-c/issues/293)) ([#b589ce3](https://github.com/edgexfoundry/device-sdk-c/commits/b589ce3))
### Build 👷
- align cmakefiles with c-utils; fix Alpine build ([#c7f3cbe](https://github.com/edgexfoundry/device-sdk-c/commits/c7f3cbe))

<a name="v1.2.2"></a>
## [v1.2.2] - 2020-07-24
### Features ✨
- Add ServerBindAddr config to set which interface to listen on ([#278](https://github.com/edgexfoundry/device-sdk-c/issues/278)) ([#67c7daa](https://github.com/edgexfoundry/device-sdk-c/commits/67c7daa))

<a name="v1.2.1"></a>
## [v1.2.1] - 2020-06-05
### Compat
- Add missing v1 post_readings function ([#8d71fec](https://github.com/edgexfoundry/device-sdk-c/commits/8d71fec))
### Examples
- Use single quotes for configuration strings. Increase retry count. ([#9bdc03e](https://github.com/edgexfoundry/device-sdk-c/commits/9bdc03e))
### Features ✨
- prevent service_start being called twice ([#f227072](https://github.com/edgexfoundry/device-sdk-c/commits/f227072))
### Refact
- use constants for MIME type names ([#bf687d4](https://github.com/edgexfoundry/device-sdk-c/commits/bf687d4))
- Use json_free_serialized_string where appropriate ([#dbcc9a3](https://github.com/edgexfoundry/device-sdk-c/commits/dbcc9a3))
### Doc
- remove superfluous fields from units in devprofiles ([#4d0f3ac](https://github.com/edgexfoundry/device-sdk-c/commits/4d0f3ac))
### Bug Fixes 🐛
- v1 compat issues * translation of request structure * memleak in post_readings ([#6fa5a9f](https://github.com/edgexfoundry/device-sdk-c/commits/6fa5a9f))
- URL-escape entity names. Remove unused metadata client fns. ([#68bbf02](https://github.com/edgexfoundry/device-sdk-c/commits/68bbf02))
### Code Refactoring ♻
- (minor) in command handler ([#4b84b54](https://github.com/edgexfoundry/device-sdk-c/commits/4b84b54))
- reduce edgex/devsdk api duplication ([#d97e10a](https://github.com/edgexfoundry/device-sdk-c/commits/d97e10a))

<a name="v1.2.0"></a>
## [v1.2.0] - 2020-05-12
### Compat
- Add --instance flag as per Go SDK ([#33a3836](https://github.com/edgexfoundry/device-sdk-c/commits/33a3836))
- use --serviceName to override default service name ([#80892bf](https://github.com/edgexfoundry/device-sdk-c/commits/80892bf))

<a name="v1.1.1"></a>
## [v1.1.1] - 2020-02-10

<a name="v1.1.0"></a>
## [v1.1.0] - 2019-10-31
### Examples
- use more conventional method of waiting for ctrl-c ([#4e8be99](https://github.com/edgexfoundry/device-sdk-c/commits/4e8be99))
### Noissue
- use correct types for setting curl options (fixes broken binary PUT on 32-bit) ([#308d9b9](https://github.com/edgexfoundry/device-sdk-c/commits/308d9b9))

<a name="v1.0.3"></a>
## [v1.0.3] - 2019-09-03

<a name="v1.0.2"></a>
## [v1.0.2] - 2019-07-29
### Noissue
- fix curl usage that was breaking cbor on 32-bit ([#0bb1fb3](https://github.com/edgexfoundry/device-sdk-c/commits/0bb1fb3))

<a name="v1.0.1"></a>
## [v1.0.1] - 2019-07-18
### Noissue
- fix integer overflow on 32-bits, memleak in autoevents ([#96ba8c2](https://github.com/edgexfoundry/device-sdk-c/commits/96ba8c2))

<a name="1.0.0"></a>
## [1.0.0] - 2019-06-17
### Refactor
- split out device management API into a seperate header ([#f82c02a](https://github.com/edgexfoundry/device-sdk-c/commits/f82c02a))
### Example
- allow override of service name and registry location ([#1d3ab23](https://github.com/edgexfoundry/device-sdk-c/commits/1d3ab23))

<a name="0.7.1"></a>
## [0.7.1] - 2018-12-10

<a name="0.7.0"></a>
## 0.7.0 - 2018-11-16

[Unreleased]: https://github.com/edgexfoundry/device-sdk-c/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.2.2...v1.3.0
[v1.2.2]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.2.1...v1.2.2
[v1.2.1]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.1.1...v1.2.0
[v1.1.1]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.0.3...v1.1.0
[v1.0.3]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.0.2...v1.0.3
[v1.0.2]: https://github.com/edgexfoundry/device-sdk-c/compare/v1.0.1...v1.0.2
[v1.0.1]: https://github.com/edgexfoundry/device-sdk-c/compare/1.0.0...v1.0.1
[1.0.0]: https://github.com/edgexfoundry/device-sdk-c/compare/0.7.1...1.0.0
[0.7.1]: https://github.com/edgexfoundry/device-sdk-c/compare/0.7.0...0.7.1
