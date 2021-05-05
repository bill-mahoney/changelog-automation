
<a name="x.y.z"></a>
## [x.y.z] - 2021-05-05
### Features ✨
- Add changing `device-modbus:` to `edgex-device-modbus:` and setting URL to master ([#6610122](https://github.com/edgexfoundry/edgex-taf/commits/6610122))
- Fixed TAF Perf to proply also pull the standard compose file ([#8d68d5e](https://github.com/edgexfoundry/edgex-taf/commits/8d68d5e))
- Switch to use edgex-mqtt-broker and removed EXPORT_HOST_PLACE_HOLDER replacement ([#405d454](https://github.com/edgexfoundry/edgex-taf/commits/405d454))
- Removed unneed sed subsitutions ([#2e10d08](https://github.com/edgexfoundry/edgex-taf/commits/2e10d08))
- Changed output of docker-compose-end-mqtt.yaml to docker-compose-mqtt.yaml ([#dfbd838](https://github.com/edgexfoundry/edgex-taf/commits/dfbd838))
- Removed references to the ${ARCH}.env files ([#6f07626](https://github.com/edgexfoundry/edgex-taf/commits/6f07626))
- Add Modbus scalability testing ([#b80dbeb](https://github.com/edgexfoundry/edgex-taf/commits/b80dbeb))
### Bug Fixes 🐛
- Update gateway token generation ([#038becc](https://github.com/edgexfoundry/edgex-taf/commits/038becc))
### Code Refactoring ♻
- Change delpoy-edgex.sh to deplaoy all security services together ([#8b12dd4](https://github.com/edgexfoundry/edgex-taf/commits/8b12dd4))
- Change gateway port to 8100 ([#c60127f](https://github.com/edgexfoundry/edgex-taf/commits/c60127f))
- Update App Service tests for change in service key ([#faf4730](https://github.com/edgexfoundry/edgex-taf/commits/faf4730))
- Switch to 2.0 Consul path ([#df0134c](https://github.com/edgexfoundry/edgex-taf/commits/df0134c))
- Update docker scripts to pull compose files from new location ([#11b0e2c](https://github.com/edgexfoundry/edgex-taf/commits/11b0e2c))
- Rename SetOutputData to SetResponseData ([#4af9c12](https://github.com/edgexfoundry/edgex-taf/commits/4af9c12))
- App Service Trigger tests for function configuration changes ([#ce9915b](https://github.com/edgexfoundry/edgex-taf/commits/ce9915b))
- Update scripts to pull compose files from edgex-compose repo ([#f25c686](https://github.com/edgexfoundry/edgex-taf/commits/f25c686))
- Use new nightly build TAF compose files ([#186834e](https://github.com/edgexfoundry/edgex-taf/commits/186834e))
### Documentation 📖
- Add badges to readme ([#1f5bfad](https://github.com/edgexfoundry/edgex-taf/commits/1f5bfad))
### Reverts
- refactor: Change gateway port to 8100
- Change image url to use dockerhub hanoi release


<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-11

<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-20
### Bug Fixes 🐛
- Fixed links to nightly-build compose files to point to edgexfoundry master ([#a5ef11f](https://github.com/edgexfoundry/edgex-taf/commits/a5ef11f))
### Code Refactoring ♻
- Adjust URL path to base compose file now under new compose-generator ([#ec3e15f](https://github.com/edgexfoundry/edgex-taf/commits/ec3e15f))
- renamed existing common.env to common-taf.env to avoid name conflict ([#bb20039](https://github.com/edgexfoundry/edgex-taf/commits/bb20039))
- added changing the database service name to `database` in previous compose files. ([#c5d729e](https://github.com/edgexfoundry/edgex-taf/commits/c5d729e))
- Replace `redis` service name with `database` so deploy works ([#40d51a5](https://github.com/edgexfoundry/edgex-taf/commits/40d51a5))
- Updated scripts to use curl and pull from new `source` folder. ([#84241da](https://github.com/edgexfoundry/edgex-taf/commits/84241da))
- Fixed typo if "-arm64" ([#105a52f](https://github.com/edgexfoundry/edgex-taf/commits/105a52f))
- Updated get-compose-file-backward.sh to use base compose file from nightly-build ([#87a1ec1](https://github.com/edgexfoundry/edgex-taf/commits/87a1ec1))
- Update scripts to handle chnage to multi-file compose files. ([#b35cc52](https://github.com/edgexfoundry/edgex-taf/commits/b35cc52))

<a name="v1.2.1"></a>
## [v1.2.1] - 2020-06-22

<a name="v1.2.0"></a>
## v1.2.0 - 2020-05-15

[Unreleased]: https://github.com/edgexfoundry/edgex-taf/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/edgex-taf/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/edgex-taf/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/edgex-taf/compare/v1.2.1...v1.3.0
[v1.2.1]: https://github.com/edgexfoundry/edgex-taf/compare/v1.2.0...v1.2.1
