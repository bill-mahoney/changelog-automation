
<a name="x.y.z"></a>
## x.y.z - 2021-05-03
### Features ✨
- Switch to Redis as the default MessageBus ([#37791f6](https://github.com/edgexfoundry/edgex-compose/commits/37791f6))
    ```
    BREAKING CHANGE:
    All services receiving Event must now be configured to use Redis as the MessageBus
    ```
- Update docker-compose's common env ([#eccf3a9](https://github.com/edgexfoundry/edgex-compose/commits/eccf3a9))
- Add README, LICENSE and previous Releases ([#694fd21](https://github.com/edgexfoundry/edgex-compose/commits/694fd21))
- Update Proxy Setup env overrides for change to use service keys ([#6e81784](https://github.com/edgexfoundry/edgex-compose/commits/6e81784))
- Add old env back and regenerate compose file ([#5646e2e](https://github.com/edgexfoundry/edgex-compose/commits/5646e2e))
- **security:** Update consul's volume on secrets folder to be writable ([#b8b15bc](https://github.com/edgexfoundry/edgex-compose/commits/b8b15bc))
- **security:** Update docker-compose security for Consul ACL Setup ([#7299cb6](https://github.com/edgexfoundry/edgex-compose/commits/7299cb6))
- **security:** Integrate device services with consul tokens ([#63](https://github.com/edgexfoundry/edgex-compose/issues/63)) ([#d3ee037](https://github.com/edgexfoundry/edgex-compose/commits/d3ee037))
- **security:** integrating consul token for edgex-sys-mgmt and app-services ([#53](https://github.com/edgexfoundry/edgex-compose/issues/53)) ([#f2a853c](https://github.com/edgexfoundry/edgex-compose/commits/f2a853c))
### Rrefactor
- Specify user explicitly for all services ([#357a6ae](https://github.com/edgexfoundry/edgex-compose/commits/357a6ae))
### Bug Fixes 🐛
- Add missing changes to ASC Tigger config overrides ([#8fd52d1](https://github.com/edgexfoundry/edgex-compose/commits/8fd52d1))
- Fixed KNOWN_SECRETS_LIST for TAF compose and added TODO comments ([#1c689a3](https://github.com/edgexfoundry/edgex-compose/commits/1c689a3))
- Fix incorrect service keys ([#69e3ca4](https://github.com/edgexfoundry/edgex-compose/commits/69e3ca4))
- Fix get-token and add missing get-consul-acl-token targets ([#292ea5b](https://github.com/edgexfoundry/edgex-compose/commits/292ea5b))
- Fixup from PR review comments ([#da72238](https://github.com/edgexfoundry/edgex-compose/commits/da72238))
- Removed duplicated text ([#9718c78](https://github.com/edgexfoundry/edgex-compose/commits/9718c78))
- Update the ui-down target to use new UI compose files. ([#837080d](https://github.com/edgexfoundry/edgex-compose/commits/837080d))
- Added ui-only back to options for Pull in the README ([#6ca50a6](https://github.com/edgexfoundry/edgex-compose/commits/6ca50a6))
- Remove redundant volume from consul container ([#0ec90fc](https://github.com/edgexfoundry/edgex-compose/commits/0ec90fc))
- Make system managment agent run as root user. ([#9410f8e](https://github.com/edgexfoundry/edgex-compose/commits/9410f8e))
- Add read-only flag to device-virtual ([#64b6dc2](https://github.com/edgexfoundry/edgex-compose/commits/64b6dc2))
- Fixed typo in env file description ([#941131a](https://github.com/edgexfoundry/edgex-compose/commits/941131a))
- Add missing Proxy Setup override for Command service host ([#b373337](https://github.com/edgexfoundry/edgex-compose/commits/b373337))
- More tweaks for TAF compose files ([#5362efa](https://github.com/edgexfoundry/edgex-compose/commits/5362efa))
- Updated copyright headers ([#07ca3ae](https://github.com/edgexfoundry/edgex-compose/commits/07ca3ae))
- **app-service:** Update env variable for SUBSCRIBEHOST on app-service ([#9de3ade](https://github.com/edgexfoundry/edgex-compose/commits/9de3ade))
- **security:** rebase to the latest from master ([#38ba5d4](https://github.com/edgexfoundry/edgex-compose/commits/38ba5d4))
- **security:** Address PR feedback ([#d348ad8](https://github.com/edgexfoundry/edgex-compose/commits/d348ad8))
- **security:** Fix insecure mode of security-proxy-setup ([#1d55c08](https://github.com/edgexfoundry/edgex-compose/commits/1d55c08))
- **security:** Update out-of-date envs of proxy-setup service ([#70e0397](https://github.com/edgexfoundry/edgex-compose/commits/70e0397))
- **security:** fix taf failing to start device-virtual Fix the issue on device-virtual and device modbus for TAF tests failed to  start them as they lost the executables of services in command section ([#47b7266](https://github.com/edgexfoundry/edgex-compose/commits/47b7266))
- **security:** Remove SECRETSTORE_HOST from proxy-setup env ([#3dae3e0](https://github.com/edgexfoundry/edgex-compose/commits/3dae3e0))
### Code Refactoring ♻
- Remove release name from compose file names ([#d6873ef](https://github.com/edgexfoundry/edgex-compose/commits/d6873ef))
- Enable adding UI service when generating a compose file ([#8997a5a](https://github.com/edgexfoundry/edgex-compose/commits/8997a5a))
- Rework structure to remove Releases folder ([#51](https://github.com/edgexfoundry/edgex-compose/issues/51)) ([#6f9eebd](https://github.com/edgexfoundry/edgex-compose/commits/6f9eebd))
- Updated Kong to user spec to 'kong:nogroup' ([#46c38bf](https://github.com/edgexfoundry/edgex-compose/commits/46c38bf))
- Run Kuiper rules engine as non-root ([#9ce5db2](https://github.com/edgexfoundry/edgex-compose/commits/9ce5db2))
- Add and use asc-common.env file ([#e25cd6e](https://github.com/edgexfoundry/edgex-compose/commits/e25cd6e))
- Add and use asc-common.env file ([#3544b21](https://github.com/edgexfoundry/edgex-compose/commits/3544b21))
- Update Setup Proxy Env Overrides for changes from Clients to Routes ([#f107669](https://github.com/edgexfoundry/edgex-compose/commits/f107669))
- Extract common ASC variables to .env files ([#71f1de2](https://github.com/edgexfoundry/edgex-compose/commits/71f1de2))
- Update ASC env overrides for function config changes ([#179f52c](https://github.com/edgexfoundry/edgex-compose/commits/179f52c))
- Populate with Compose Builder from developer-scripts ([#f787e88](https://github.com/edgexfoundry/edgex-compose/commits/f787e88))
### Documentation 📖
- Add badges to readme ([#478350d](https://github.com/edgexfoundry/edgex-compose/commits/478350d))
### Build 👷
- Update to CE version of Portainer ([#8549066](https://github.com/edgexfoundry/edgex-compose/commits/8549066))
- Add Jenkinsfile to enable TAF smoke tests are run. ([#4e9deb2](https://github.com/edgexfoundry/edgex-compose/commits/4e9deb2))

[Unreleased]: https://github.com/edgexfoundry/edgex-compose/compare/x.y.z...HEAD
