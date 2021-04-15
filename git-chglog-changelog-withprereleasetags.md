<a name="unreleased"></a>
## [Unreleased]


<a name="v2.0.0-dev.43"></a>
## [v2.0.0-dev.43] - 2021-04-07
### Refactor
- Replace file based with use of Secret Provider to get Access Tokens ([#784](https://github.com/bill-mahoney/app-functions-sdk-go/issues/784))

### BREAKING CHANGE

All App Services running with the secure Edgex Stack now need to have the SecretStore configured, a Vault token created and run with EDGEX_SECURITY_SECRET_STORE=true.


<a name="v2.0.0-dev.42"></a>
## [v2.0.0-dev.42] - 2021-04-07
### Build
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#781](https://github.com/bill-mahoney/app-functions-sdk-go/issues/781))


<a name="v2.0.0-dev.41"></a>
## [v2.0.0-dev.41] - 2021-04-06
### Refactor
- Switch to 2.0 Consul path ([#782](https://github.com/bill-mahoney/app-functions-sdk-go/issues/782))

### BREAKING CHANGE

Consul configuration now under the `/2.0/` path


<a name="v2.0.0-dev.40"></a>
## [v2.0.0-dev.40] - 2021-03-31
### Refactor
- Update Version Check to use V2 endpoint ([#778](https://github.com/bill-mahoney/app-functions-sdk-go/issues/778))


<a name="v2.0.0-dev.39"></a>
## [v2.0.0-dev.39] - 2021-03-31
### Fix
- Fix webserver to use ServerBindAddr only is not blank as rest of EdgeX Services ([#776](https://github.com/bill-mahoney/app-functions-sdk-go/issues/776))

### BREAKING CHANGE

Webserver will be locked down to listen just to `Host` value when If `ServerBindAddr ` is blank


<a name="v2.0.0-dev.38"></a>
## [v2.0.0-dev.38] - 2021-03-30
### Build
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#773](https://github.com/bill-mahoney/app-functions-sdk-go/issues/773))


<a name="v2.0.0-dev.37"></a>
## [v2.0.0-dev.37] - 2021-03-30
### Feat
- Enable Registry and Config access token ([#772](https://github.com/bill-mahoney/app-functions-sdk-go/issues/772))


<a name="v2.0.0-dev.36"></a>
## [v2.0.0-dev.36] - 2021-03-29
### Refactor
- Update code for Created & Modified removed from Event DTO ([#771](https://github.com/bill-mahoney/app-functions-sdk-go/issues/771))


<a name="v2.0.0-dev.35"></a>
## [v2.0.0-dev.35] - 2021-03-25
### Refactor
- **v2:** Update Custom Trigger Configuration ([#764](https://github.com/bill-mahoney/app-functions-sdk-go/issues/764))


<a name="v2.0.0-dev.34"></a>
## [v2.0.0-dev.34] - 2021-03-25
### Build
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap/v2 ([#762](https://github.com/bill-mahoney/app-functions-sdk-go/issues/762))


<a name="v2.0.0-dev.33"></a>
## [v2.0.0-dev.33] - 2021-03-25
### Build
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#757](https://github.com/bill-mahoney/app-functions-sdk-go/issues/757))

### Feat
- Add GetAppSetting convenience API ([#761](https://github.com/bill-mahoney/app-functions-sdk-go/issues/761))

### Fix
- **v2:** Expose Response Data ([#759](https://github.com/bill-mahoney/app-functions-sdk-go/issues/759))


<a name="v2.0.0-dev.32"></a>
## [v2.0.0-dev.32] - 2021-03-24
### Feat
- Add custom structured configuration capability ([#753](https://github.com/bill-mahoney/app-functions-sdk-go/issues/753))


<a name="v2.0.0-dev.31"></a>
## [v2.0.0-dev.31] - 2021-03-19
### Refactor
- Change to using service keys for names in Clients configuration ([#747](https://github.com/bill-mahoney/app-functions-sdk-go/issues/747))

### BREAKING CHANGE

Clients configuration has changed and must be updated to use service keys for names


<a name="v2.0.0-dev.30"></a>
## [v2.0.0-dev.30] - 2021-03-19
### Refactor
- Adjust code for latest go-mod-core contracts changes ([#750](https://github.com/bill-mahoney/app-functions-sdk-go/issues/750))


<a name="v2.0.0-dev.29"></a>
## [v2.0.0-dev.29] - 2021-03-18
### Refactor
- Remove unneeded call to validate CBOR encoded Event request ([#746](https://github.com/bill-mahoney/app-functions-sdk-go/issues/746))


<a name="v2.0.0-dev.28"></a>
## [v2.0.0-dev.28] - 2021-03-18
### Refactor
- Rework SDK to use Interfaces and factory methods ([#741](https://github.com/bill-mahoney/app-functions-sdk-go/issues/741))

### BREAKING CHANGE

App Services will require refactoring to use new interfaces  and factory methods


<a name="v2.0.0-dev.27"></a>
## [v2.0.0-dev.27] - 2021-03-04
### Feat
- Add new FilterBySourceName function ([#731](https://github.com/bill-mahoney/app-functions-sdk-go/issues/731))

### BREAKING CHANGE

V1 API's no longer supported


<a name="v2.0.0-dev.26"></a>
## [v2.0.0-dev.26] - 2021-03-04
### Refactor
- Remove V1 API code and swagger ([#730](https://github.com/bill-mahoney/app-functions-sdk-go/issues/730))

### BREAKING CHANGE

V1 API's no longer supported


<a name="v2.0.0-dev.25"></a>
## [v2.0.0-dev.25] - 2021-03-04
### Refactor
- Consolidate function pipeline configuration ([#728](https://github.com/bill-mahoney/app-functions-sdk-go/issues/728))


<a name="v2.0.0-dev.24"></a>
## [v2.0.0-dev.24] - 2021-03-01
### Build
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#715](https://github.com/bill-mahoney/app-functions-sdk-go/issues/715))


<a name="v2.0.0-dev.23"></a>
## [v2.0.0-dev.23] - 2021-02-26
### Refactor
- Restructure Trigger configuration ([#724](https://github.com/bill-mahoney/app-functions-sdk-go/issues/724))

### BREAKING CHANGE

- Renamed `Binding` to `Trigger`
- Removed deprecated `MessageBus` trigger type, replaced by`edgex-messagebus`
- Renamed `MessageBus` to `EdgexMessageBus`
- Move `EdgexMessageBus` and `ExternalMqtt` under `Trigger` configuration


<a name="v2.0.0-dev.22"></a>
## [v2.0.0-dev.22] - 2021-02-25
### Refactor
- Remove deprecated environment variables and related code ([#718](https://github.com/bill-mahoney/app-functions-sdk-go/issues/718))

### BREAKING CHANGE

The following environment variables no longer supported:
- `edgex_profile` (replaced by uppercase version)
- `edgex_service`


<a name="v2.0.0-dev.21"></a>
## [v2.0.0-dev.21] - 2021-02-25
### Refactor
- Rename MqttBroker configuration to ExternalMqtt ([#717](https://github.com/bill-mahoney/app-functions-sdk-go/issues/717))

### BREAKING CHANGE

Configuration section name changed


<a name="v2.0.0-dev.20"></a>
## [v2.0.0-dev.20] - 2021-02-25
### Refactor
- Rework secrets for HTTP Export so value in InsecureSecrets can be overridden ([#714](https://github.com/bill-mahoney/app-functions-sdk-go/issues/714))

### BREAKING CHANGE

Parameters have changed for HTTP Post/Put with SecretHeader


<a name="v2.0.0-dev.19"></a>
## [v2.0.0-dev.19] - 2021-02-23
### Fix
- Errors in dynamic pipeline updates allow previous pipeline to run, hiding the errors ([#711](https://github.com/bill-mahoney/app-functions-sdk-go/issues/711))


<a name="v2.0.0-dev.18"></a>
## [v2.0.0-dev.18] - 2021-02-23
### Fix
- Return 400 (BadRequest) on DTO validation failure ([#710](https://github.com/bill-mahoney/app-functions-sdk-go/issues/710))


<a name="v2.0.0-dev.17"></a>
## [v2.0.0-dev.17] - 2021-02-22
### Refactor
- Update to latest modules and adjust code for changes ([#708](https://github.com/bill-mahoney/app-functions-sdk-go/issues/708))


<a name="v2.0.0-dev.16"></a>
## [v2.0.0-dev.16] - 2021-02-22
### Feat
- Add secrets capability to Encryption pipeline function ([#706](https://github.com/bill-mahoney/app-functions-sdk-go/issues/706))


<a name="v2.0.0-dev.15"></a>
## [v2.0.0-dev.15] - 2021-02-19
### Feat
- Port service template from hanoi branch ([#703](https://github.com/bill-mahoney/app-functions-sdk-go/issues/703))


<a name="v2.0.0-dev.14"></a>
## [v2.0.0-dev.14] - 2021-02-16
### Feat
- Add debug logging of the Event Tags


<a name="v2.0.0-dev.13"></a>
## [v2.0.0-dev.13] - 2021-02-16
### Fix
- **sdk:** Normalize Trigger Factory Returns ([#699](https://github.com/bill-mahoney/app-functions-sdk-go/issues/699))


<a name="v2.0.0-dev.12"></a>
## [v2.0.0-dev.12] - 2021-02-12
### Build
- Update to use go-mod-messaging v2 ([#638](https://github.com/bill-mahoney/app-functions-sdk-go/issues/638))
- **deps:** bump github.com/stretchr/testify from 1.6.1 to 1.7.0 ([#636](https://github.com/bill-mahoney/app-functions-sdk-go/issues/636))
- **deps:** bump github.com/google/uuid from 1.1.4 to 1.1.5 ([#639](https://github.com/bill-mahoney/app-functions-sdk-go/issues/639))
- **deps:** bump github.com/google/uuid from 1.1.2 to 1.1.4 ([#626](https://github.com/bill-mahoney/app-functions-sdk-go/issues/626))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#629](https://github.com/bill-mahoney/app-functions-sdk-go/issues/629))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#627](https://github.com/bill-mahoney/app-functions-sdk-go/issues/627))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#628](https://github.com/bill-mahoney/app-functions-sdk-go/issues/628))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#608](https://github.com/bill-mahoney/app-functions-sdk-go/issues/608))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts

### Ci
- standardize dockerfiles ([#610](https://github.com/bill-mahoney/app-functions-sdk-go/issues/610))

### Feat
- Update Filters for V2 DTO changes ([#680](https://github.com/bill-mahoney/app-functions-sdk-go/issues/680))
- Add debug logging of Event/Reading details ([#666](https://github.com/bill-mahoney/app-functions-sdk-go/issues/666))
- Expect V2 Event DTO from triggers. ([#616](https://github.com/bill-mahoney/app-functions-sdk-go/issues/616))
- Allow for multiple MessageBus subscriptions ([#625](https://github.com/bill-mahoney/app-functions-sdk-go/issues/625))
- Remove MarkAsPushed feature ([#607](https://github.com/bill-mahoney/app-functions-sdk-go/issues/607))
- Remove deprecated MQTTSend pipeline function ([#592](https://github.com/bill-mahoney/app-functions-sdk-go/issues/592))
- Remove remote logging service capability ([#585](https://github.com/bill-mahoney/app-functions-sdk-go/issues/585))
- **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/bill-mahoney/app-functions-sdk-go/issues/644))
- **sdk:** Add MakeItStop ([#613](https://github.com/bill-mahoney/app-functions-sdk-go/issues/613))
- **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/bill-mahoney/app-functions-sdk-go/issues/587))
- **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/bill-mahoney/app-functions-sdk-go/issues/589))

### Fix
- Fixed and enhanced Filter function debug messages ([#686](https://github.com/bill-mahoney/app-functions-sdk-go/issues/686))
- **sdk:** Change default TargetType to be AddEventRequest ([#689](https://github.com/bill-mahoney/app-functions-sdk-go/issues/689))

### Refactor
- Dynamically process either AddEventRequest DTO or Event DTO ([#693](https://github.com/bill-mahoney/app-functions-sdk-go/issues/693))
- Consume V2 version of edgex go-mods ([#649](https://github.com/bill-mahoney/app-functions-sdk-go/issues/649))
- Refactor V2 API /secrets to be singular /secret ([#648](https://github.com/bill-mahoney/app-functions-sdk-go/issues/648))
- Make SDK a V2 Go Module ([#643](https://github.com/bill-mahoney/app-functions-sdk-go/issues/643))
- Use common SecretsRequest DTO from go-mod-core-contracts ([#622](https://github.com/bill-mahoney/app-functions-sdk-go/issues/622))
- Refactor to use new SecretProvider fro go-mod-bootstrap ([#604](https://github.com/bill-mahoney/app-functions-sdk-go/issues/604))


<a name="v1.3.2-dev.1"></a>
## [v1.3.2-dev.1] - 2021-02-12
### Feat
- Hanoi: Add template for creating new App Service ([#679](https://github.com/bill-mahoney/app-functions-sdk-go/issues/679))

### Fix
- Upgrade to go-mod-messaging with ZMQ fix ([#660](https://github.com/bill-mahoney/app-functions-sdk-go/issues/660))


<a name="v2.0.0-dev.11"></a>
## [v2.0.0-dev.11] - 2021-02-11
### Fix
- **sdk:** Change default TargetType to be AddEventRequest ([#689](https://github.com/bill-mahoney/app-functions-sdk-go/issues/689))


<a name="v2.0.0-dev.10"></a>
## [v2.0.0-dev.10] - 2021-02-09
### Fix
- Fixed and enhanced Filter function debug messages ([#686](https://github.com/bill-mahoney/app-functions-sdk-go/issues/686))


<a name="v2.0.0-dev.9"></a>
## [v2.0.0-dev.9] - 2021-02-08
### Build
- Update to use go-mod-messaging v2 ([#638](https://github.com/bill-mahoney/app-functions-sdk-go/issues/638))
- **deps:** bump github.com/stretchr/testify from 1.6.1 to 1.7.0 ([#636](https://github.com/bill-mahoney/app-functions-sdk-go/issues/636))
- **deps:** bump github.com/google/uuid from 1.1.4 to 1.1.5 ([#639](https://github.com/bill-mahoney/app-functions-sdk-go/issues/639))
- **deps:** bump github.com/google/uuid from 1.1.2 to 1.1.4 ([#626](https://github.com/bill-mahoney/app-functions-sdk-go/issues/626))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#629](https://github.com/bill-mahoney/app-functions-sdk-go/issues/629))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#627](https://github.com/bill-mahoney/app-functions-sdk-go/issues/627))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#628](https://github.com/bill-mahoney/app-functions-sdk-go/issues/628))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#608](https://github.com/bill-mahoney/app-functions-sdk-go/issues/608))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts

### Ci
- standardize dockerfiles ([#610](https://github.com/bill-mahoney/app-functions-sdk-go/issues/610))

### Feat
- Update Filters for V2 DTO changes ([#680](https://github.com/bill-mahoney/app-functions-sdk-go/issues/680))
- Add debug logging of Event/Reading details ([#666](https://github.com/bill-mahoney/app-functions-sdk-go/issues/666))
- Expect V2 Event DTO from triggers. ([#616](https://github.com/bill-mahoney/app-functions-sdk-go/issues/616))
- Allow for multiple MessageBus subscriptions ([#625](https://github.com/bill-mahoney/app-functions-sdk-go/issues/625))
- Remove MarkAsPushed feature ([#607](https://github.com/bill-mahoney/app-functions-sdk-go/issues/607))
- Remove deprecated MQTTSend pipeline function ([#592](https://github.com/bill-mahoney/app-functions-sdk-go/issues/592))
- Remove remote logging service capability ([#585](https://github.com/bill-mahoney/app-functions-sdk-go/issues/585))
- **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/bill-mahoney/app-functions-sdk-go/issues/644))
- **sdk:** Add MakeItStop ([#613](https://github.com/bill-mahoney/app-functions-sdk-go/issues/613))
- **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/bill-mahoney/app-functions-sdk-go/issues/587))
- **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/bill-mahoney/app-functions-sdk-go/issues/589))

### Refactor
- Consume V2 version of edgex go-mods ([#649](https://github.com/bill-mahoney/app-functions-sdk-go/issues/649))
- Refactor V2 API /secrets to be singular /secret ([#648](https://github.com/bill-mahoney/app-functions-sdk-go/issues/648))
- Make SDK a V2 Go Module ([#643](https://github.com/bill-mahoney/app-functions-sdk-go/issues/643))
- Use common SecretsRequest DTO from go-mod-core-contracts ([#622](https://github.com/bill-mahoney/app-functions-sdk-go/issues/622))
- Refactor to use new SecretProvider fro go-mod-bootstrap ([#604](https://github.com/bill-mahoney/app-functions-sdk-go/issues/604))


<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-04
### Fix
- Upgrade to go-mod-messaging with ZMQ fix ([#660](https://github.com/bill-mahoney/app-functions-sdk-go/issues/660))


<a name="v2.0.0-dev.8"></a>
## [v2.0.0-dev.8] - 2021-01-30
### Build
- Update to use go-mod-messaging v2 ([#638](https://github.com/bill-mahoney/app-functions-sdk-go/issues/638))
- **deps:** bump github.com/stretchr/testify from 1.6.1 to 1.7.0 ([#636](https://github.com/bill-mahoney/app-functions-sdk-go/issues/636))
- **deps:** bump github.com/google/uuid from 1.1.4 to 1.1.5 ([#639](https://github.com/bill-mahoney/app-functions-sdk-go/issues/639))
- **deps:** bump github.com/google/uuid from 1.1.2 to 1.1.4 ([#626](https://github.com/bill-mahoney/app-functions-sdk-go/issues/626))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#629](https://github.com/bill-mahoney/app-functions-sdk-go/issues/629))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#627](https://github.com/bill-mahoney/app-functions-sdk-go/issues/627))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#628](https://github.com/bill-mahoney/app-functions-sdk-go/issues/628))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#608](https://github.com/bill-mahoney/app-functions-sdk-go/issues/608))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts

### Ci
- standardize dockerfiles ([#610](https://github.com/bill-mahoney/app-functions-sdk-go/issues/610))

### Feat
- Add debug logging of Event/Reading details ([#666](https://github.com/bill-mahoney/app-functions-sdk-go/issues/666))
- Expect V2 Event DTO from triggers. ([#616](https://github.com/bill-mahoney/app-functions-sdk-go/issues/616))
- Allow for multiple MessageBus subscriptions ([#625](https://github.com/bill-mahoney/app-functions-sdk-go/issues/625))
- Remove MarkAsPushed feature ([#607](https://github.com/bill-mahoney/app-functions-sdk-go/issues/607))
- Remove deprecated MQTTSend pipeline function ([#592](https://github.com/bill-mahoney/app-functions-sdk-go/issues/592))
- Remove remote logging service capability ([#585](https://github.com/bill-mahoney/app-functions-sdk-go/issues/585))
- **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/bill-mahoney/app-functions-sdk-go/issues/644))
- **sdk:** Add MakeItStop ([#613](https://github.com/bill-mahoney/app-functions-sdk-go/issues/613))
- **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/bill-mahoney/app-functions-sdk-go/issues/587))
- **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/bill-mahoney/app-functions-sdk-go/issues/589))

### Refactor
- Consume V2 version of edgex go-mods ([#649](https://github.com/bill-mahoney/app-functions-sdk-go/issues/649))
- Refactor V2 API /secrets to be singular /secret ([#648](https://github.com/bill-mahoney/app-functions-sdk-go/issues/648))
- Make SDK a V2 Go Module ([#643](https://github.com/bill-mahoney/app-functions-sdk-go/issues/643))
- Use common SecretsRequest DTO from go-mod-core-contracts ([#622](https://github.com/bill-mahoney/app-functions-sdk-go/issues/622))
- Refactor to use new SecretProvider fro go-mod-bootstrap ([#604](https://github.com/bill-mahoney/app-functions-sdk-go/issues/604))


<a name="v1.3.1-dev.1"></a>
## [v1.3.1-dev.1] - 2021-01-26
### Fix
- Upgrade to go-mod-messaging with ZMQ fix ([#660](https://github.com/bill-mahoney/app-functions-sdk-go/issues/660))


<a name="v2.0.0-dev.7"></a>
## [v2.0.0-dev.7] - 2021-01-25
### Feat
- Expect V2 Event DTO from triggers. ([#616](https://github.com/bill-mahoney/app-functions-sdk-go/issues/616))


<a name="v2.0.0-dev.6"></a>
## [v2.0.0-dev.6] - 2021-01-22
### Feat
- **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/bill-mahoney/app-functions-sdk-go/issues/644))


<a name="v2.0.0-dev.5"></a>
## [v2.0.0-dev.5] - 2021-01-22
### Build
- **deps:** bump github.com/stretchr/testify from 1.6.1 to 1.7.0 ([#636](https://github.com/bill-mahoney/app-functions-sdk-go/issues/636))


<a name="v2.0.0-dev.4"></a>
## [v2.0.0-dev.4] - 2021-01-21
### Refactor
- Consume V2 version of edgex go-mods ([#649](https://github.com/bill-mahoney/app-functions-sdk-go/issues/649))


<a name="v2.0.0-dev.3"></a>
## [v2.0.0-dev.3] - 2021-01-21
### Refactor
- Refactor V2 API /secrets to be singular /secret ([#648](https://github.com/bill-mahoney/app-functions-sdk-go/issues/648))


<a name="v2.0.0-dev.2"></a>
## [v2.0.0-dev.2] - 2021-01-20
### Build
- **deps:** bump github.com/google/uuid from 1.1.4 to 1.1.5 ([#639](https://github.com/bill-mahoney/app-functions-sdk-go/issues/639))


<a name="v2.0.0-dev.1"></a>
## [v2.0.0-dev.1] - 2021-01-15
### Build
- Update to use go-mod-messaging v2 ([#638](https://github.com/bill-mahoney/app-functions-sdk-go/issues/638))
- **deps:** bump github.com/google/uuid from 1.1.2 to 1.1.4 ([#626](https://github.com/bill-mahoney/app-functions-sdk-go/issues/626))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#629](https://github.com/bill-mahoney/app-functions-sdk-go/issues/629))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#627](https://github.com/bill-mahoney/app-functions-sdk-go/issues/627))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#628](https://github.com/bill-mahoney/app-functions-sdk-go/issues/628))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#608](https://github.com/bill-mahoney/app-functions-sdk-go/issues/608))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts

### Ci
- standardize dockerfiles ([#610](https://github.com/bill-mahoney/app-functions-sdk-go/issues/610))

### Feat
- Allow for multiple MessageBus subscriptions ([#625](https://github.com/bill-mahoney/app-functions-sdk-go/issues/625))
- Remove MarkAsPushed feature ([#607](https://github.com/bill-mahoney/app-functions-sdk-go/issues/607))
- Remove deprecated MQTTSend pipeline function ([#592](https://github.com/bill-mahoney/app-functions-sdk-go/issues/592))
- Remove remote logging service capability ([#585](https://github.com/bill-mahoney/app-functions-sdk-go/issues/585))
- **sdk:** Add MakeItStop ([#613](https://github.com/bill-mahoney/app-functions-sdk-go/issues/613))
- **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/bill-mahoney/app-functions-sdk-go/issues/587))
- **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/bill-mahoney/app-functions-sdk-go/issues/589))

### Refactor
- Make SDK a V2 Go Module ([#643](https://github.com/bill-mahoney/app-functions-sdk-go/issues/643))
- Use common SecretsRequest DTO from go-mod-core-contracts ([#622](https://github.com/bill-mahoney/app-functions-sdk-go/issues/622))
- Refactor to use new SecretProvider fro go-mod-bootstrap ([#604](https://github.com/bill-mahoney/app-functions-sdk-go/issues/604))


<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-11
### Build
- Use latest go-mod-core-contracts and fix build errors due to name change ([#543](https://github.com/bill-mahoney/app-functions-sdk-go/issues/543))
- Switch to use Go 1.15 ([#478](https://github.com/bill-mahoney/app-functions-sdk-go/issues/478))
- Enable DependaBot via YML file, rather than external BOT
- Enable DependaBot via YML file rather than external BOT
- Enable DependaBot via YML file rather than external BOT
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#566](https://github.com/bill-mahoney/app-functions-sdk-go/issues/566))
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#558](https://github.com/bill-mahoney/app-functions-sdk-go/issues/558))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#559](https://github.com/bill-mahoney/app-functions-sdk-go/issues/559))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#545](https://github.com/bill-mahoney/app-functions-sdk-go/issues/545))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#539](https://github.com/bill-mahoney/app-functions-sdk-go/issues/539))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#562](https://github.com/bill-mahoney/app-functions-sdk-go/issues/562))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#553](https://github.com/bill-mahoney/app-functions-sdk-go/issues/553))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#564](https://github.com/bill-mahoney/app-functions-sdk-go/issues/564))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#563](https://github.com/bill-mahoney/app-functions-sdk-go/issues/563))
- **deps:** bump github.com/google/uuid from 1.1.1 to 1.1.2 ([#458](https://github.com/bill-mahoney/app-functions-sdk-go/issues/458))
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#493](https://github.com/bill-mahoney/app-functions-sdk-go/issues/493))
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#492](https://github.com/bill-mahoney/app-functions-sdk-go/issues/492))
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#496](https://github.com/bill-mahoney/app-functions-sdk-go/issues/496))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#565](https://github.com/bill-mahoney/app-functions-sdk-go/issues/565))
- **deps:** bump github.com/gorilla/mux from 1.7.4 to 1.8.0
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#451](https://github.com/bill-mahoney/app-functions-sdk-go/issues/451))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#447](https://github.com/bill-mahoney/app-functions-sdk-go/issues/447))
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/stretchr/testify from 1.5.1 to 1.6.1
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap
- **deps:** bump github.com/edgexfoundry/go-mod-secrets

### Chore
- remove mongo DB implementation ([#399](https://github.com/bill-mahoney/app-functions-sdk-go/issues/399))

### Ci
- update scopes and types for conventional commits ([#561](https://github.com/bill-mahoney/app-functions-sdk-go/issues/561))
- update scope to include "deps" in semantic.yml
- add scopes to pr-bot ([#411](https://github.com/bill-mahoney/app-functions-sdk-go/issues/411))

### Docs
- addition of version and LTS refs to README per arch's meeting
- update pr template to include dependencies question ([#382](https://github.com/bill-mahoney/app-functions-sdk-go/issues/382))

### Feat
- Add V2 Version endpoint ([#435](https://github.com/bill-mahoney/app-functions-sdk-go/issues/435))
- add message bootstrap handler, fixes [#423](https://github.com/bill-mahoney/app-functions-sdk-go/issues/423) ([#424](https://github.com/bill-mahoney/app-functions-sdk-go/issues/424))
- V2 Swagger Doc Design ([#422](https://github.com/bill-mahoney/app-functions-sdk-go/issues/422))
- Implement V2 Ping endpoint and V2 layers ([#433](https://github.com/bill-mahoney/app-functions-sdk-go/issues/433))
- Implement transform to add Tags to Event ([#467](https://github.com/bill-mahoney/app-functions-sdk-go/issues/467))
- Add logging of service version and total startup time ([#434](https://github.com/bill-mahoney/app-functions-sdk-go/issues/434))
- Implement V2 Secrets endpoint ([#441](https://github.com/bill-mahoney/app-functions-sdk-go/issues/441))
- Implement V2 Trigger endpoint ([#440](https://github.com/bill-mahoney/app-functions-sdk-go/issues/440))
- Implement V2 Config endpoint ([#437](https://github.com/bill-mahoney/app-functions-sdk-go/issues/437))
- Implement V2 Metrics endpoint ([#436](https://github.com/bill-mahoney/app-functions-sdk-go/issues/436))
- Add ability to export via HTTP PUT with secret header support ([#546](https://github.com/bill-mahoney/app-functions-sdk-go/issues/546))
- configurable ListenAndServe address, fixes [#405](https://github.com/bill-mahoney/app-functions-sdk-go/issues/405) ([#406](https://github.com/bill-mahoney/app-functions-sdk-go/issues/406))
- **sdk:** Add background publisher to MessageBus ([#466](https://github.com/bill-mahoney/app-functions-sdk-go/issues/466))
- **sdk:** expose RegistryClient on SDK ([#501](https://github.com/bill-mahoney/app-functions-sdk-go/issues/501))
- **sdk:** Expose SDK EdgeX clients ([#525](https://github.com/bill-mahoney/app-functions-sdk-go/issues/525))
- **triggers:** Add MQTT Trigger with secure connection options ([#498](https://github.com/bill-mahoney/app-functions-sdk-go/issues/498))

### Fix
- Fix response content type issue 567 ([#568](https://github.com/bill-mahoney/app-functions-sdk-go/issues/568))
- http trigger response can set content-type ([#551](https://github.com/bill-mahoney/app-functions-sdk-go/issues/551))
- Adjust timing so test doesn't fail intermittently ([#549](https://github.com/bill-mahoney/app-functions-sdk-go/issues/549))
- backwards compatibility broken by [#406](https://github.com/bill-mahoney/app-functions-sdk-go/issues/406), fixes [#408](https://github.com/bill-mahoney/app-functions-sdk-go/issues/408) ([#409](https://github.com/bill-mahoney/app-functions-sdk-go/issues/409))
- Set Redis password in MessageBus.Optional when using redisstreams ([#534](https://github.com/bill-mahoney/app-functions-sdk-go/issues/534))
- Skip compatibility check when Core Data's version is 0.0.0 (developer build) ([#533](https://github.com/bill-mahoney/app-functions-sdk-go/issues/533))
- Make `path` property required for the Secrets V1 & V2 APIs ([#497](https://github.com/bill-mahoney/app-functions-sdk-go/issues/497))
- Data races detected from messagbus unit test [#488](https://github.com/bill-mahoney/app-functions-sdk-go/issues/488) ([#489](https://github.com/bill-mahoney/app-functions-sdk-go/issues/489))
- Fix  unit tests that fail when using Go 1.15 ([#485](https://github.com/bill-mahoney/app-functions-sdk-go/issues/485))
- Add locking around MQTT client setup and around connecting to avoid race conditions. ([#474](https://github.com/bill-mahoney/app-functions-sdk-go/issues/474))
- Request DTO's RequestId is not required. Can be blank or a valid UUID ([#475](https://github.com/bill-mahoney/app-functions-sdk-go/issues/475))
- Data races detected from Batch function [#448](https://github.com/bill-mahoney/app-functions-sdk-go/issues/448) ([#449](https://github.com/bill-mahoney/app-functions-sdk-go/issues/449))
- Rename swagger file to use `yaml` extension. ([#465](https://github.com/bill-mahoney/app-functions-sdk-go/issues/465))
- Trigger API schema type of `text` for errors is invalid, should be `string` ([#453](https://github.com/bill-mahoney/app-functions-sdk-go/issues/453))
- V2 Secrets return proper 201, 400 or 500 status codes, not 207. ([#443](https://github.com/bill-mahoney/app-functions-sdk-go/issues/443))
- Allow startup duration/interval to be overridden via environement vars ([#426](https://github.com/bill-mahoney/app-functions-sdk-go/issues/426))
- InsecureSecrets change processing should update SecretProvider.LastUpdated ([#420](https://github.com/bill-mahoney/app-functions-sdk-go/issues/420))
- app-service-configurable issue 74 ([#383](https://github.com/bill-mahoney/app-functions-sdk-go/issues/383))
- **sdk:** Fix version check to handle new core-data `dev` versions. ([#416](https://github.com/bill-mahoney/app-functions-sdk-go/issues/416))
- **triggers:** MQTT subscribe via onConnect handler so re-subscribe on reconnects ([#537](https://github.com/bill-mahoney/app-functions-sdk-go/issues/537))

### Refactor
- Replace calling NewBaseResponseWithoutMessage with NewBaseResponse ([#557](https://github.com/bill-mahoney/app-functions-sdk-go/issues/557))
- Change all unit tests to use logger.NewMockCient() ([#555](https://github.com/bill-mahoney/app-functions-sdk-go/issues/555))
- Refactor V2 API to use new errors mechanism for go-mo-core-contracts ([#494](https://github.com/bill-mahoney/app-functions-sdk-go/issues/494))
- Remove Client monitoring. ([#386](https://github.com/bill-mahoney/app-functions-sdk-go/issues/386))

### Revert
- **store-forward:** removal of Mongo implementation ([#414](https://github.com/bill-mahoney/app-functions-sdk-go/issues/414))


<a name="v1.2.0"></a>
## [v1.2.0] - 2020-06-11
### Docs
- update changelog ([#379](https://github.com/bill-mahoney/app-functions-sdk-go/issues/379))
- update changelog

### Feat
- Add ability to Filter functions to reverse the logic to filter out specified names ([#375](https://github.com/bill-mahoney/app-functions-sdk-go/issues/375))

### Fix
- fixed log message formatting ([#378](https://github.com/bill-mahoney/app-functions-sdk-go/issues/378))
- Allow overrides that have empty/blank value ([#374](https://github.com/bill-mahoney/app-functions-sdk-go/issues/374))


<a name="v1.1.0"></a>
## [v1.1.0] - 2020-05-12
### Bug
- **README:** Fix example code in README to not panic if LoggingClient not initialized
- **urlclient:** Update contracts version to fix bug in URLClient.

### Build
- Updated to latest go-mod-core-contract for bug fix ([#364](https://github.com/bill-mahoney/app-functions-sdk-go/issues/364))
- Update relevant files in app-functions-sdk-go for Go 1.13. Close [#280](https://github.com/bill-mahoney/app-functions-sdk-go/issues/280)
- update go version to 1.13
- **Jenkinsfile:** Pipeline changes for Geneva release
- **go.mod:** update dependencies

### Ci
- github actions experiment ([#366](https://github.com/bill-mahoney/app-functions-sdk-go/issues/366))
- allow merge in git history
- improve conventional commit conformance
- **jenkins:** remove sandbox file

### Docs
- update links to point to v1.2
- move docs to edgex-docs
- adding batch to TOC
- batch documentation created
- Update PR Template based on feedback
- Add webserver usage to ToC
- **pr-template:** remove contribution guidelines from PR checklist since commitlint checks this

### Feat
- Add ability for command-line and environment override of service name ([#356](https://github.com/bill-mahoney/app-functions-sdk-go/issues/356))
- Integrate with new redis streams message bus implementation
- batch and send
- **appsdk:** Add support for HTTPs on REST trigger
- **appsdk:** Add support for HTTPs on REST trigger
- **bootstrap:** Integrate go-mod-bootstrap for common bootstraping
- **configurable:** add JSONLogic
- **configurable:** add batch functions
- **configurable:** add mqtt secret support
- **configurable:** support secrets for http export
- **core contracts:** Upgrade to latest Core Contracts for Reading enhancements
- **http-export:** add support for auth token in header
- **jsonlogic:** add filter feature of jsonlogic
- **mqtt:** add security provider support for mqtt connection
- **sdk:** Implement StoreSecrets in app functions SDK
- **sdk:** Add support for insecure secrets for when running non secure mode
- **sdk:** Add helper function to SDK to get string slice from App Settings.
- **sdk:** Add full path to secrets api route
- **security:** Add second SecurityStore client for service specific secrets

### Fix
- Remove code that returns empty credentials for Redis
- Use correct parameter key name for MQTTSecretSend AuthMode in configurable pipeline ([#358](https://github.com/bill-mahoney/app-functions-sdk-go/issues/358))
- Implement smarter configuration update processing ([#354](https://github.com/bill-mahoney/app-functions-sdk-go/issues/354))
- Added longer sleep to fix intermittent unit test failure on ARM ([#352](https://github.com/bill-mahoney/app-functions-sdk-go/issues/352))
- JSONLogic now runs rules everytime insted of 1st time
- Handle deprecated edgex_service env variable
- Use credentials from Database config if not found in InsecureSecrets
- Add more sleep time to Batch and Send unit test to fix ARM CI failures ([#361](https://github.com/bill-mahoney/app-functions-sdk-go/issues/361))
- **SecretClient:** Initialization of secret client retry logic
- **SecurityProvider:** Make initialization of secret clients optional
- **batch:** 2nd batch hanging in count mode
- **go.mod:** Removed wrong version of ZMQ package used.
- **profile:** Set profile properly in service's service key when env override used
- **retry loop:** Wrap version check and DB connection is a retry loop instead of sending an error ([#345](https://github.com/bill-mahoney/app-functions-sdk-go/issues/345))
- **trigger:** invoke connect on initialization

### Refact
- **sdk:** Update usage of NewSecretClient to use the latest go-mod-secrets

### Refactor
- Change serviceName override to be ServiceKey ([#365](https://github.com/bill-mahoney/app-functions-sdk-go/issues/365))
- Updated to use latest core-contracts changes
- **CBOR:** Replace ugorji/go with fixmacker/cbor
- **sdk:** Add MQTT MessageBus Support
- **tests:** Fix order of expected vs actual and other clean up

### Test
- fix race condition in batch tests
- fix timing issue with Batch transform test

### BREAKING CHANGE

Inserting preceding "-" when replacing `<profile>` in the service key has been removed so the use is more flexible.  The only service using the <profile> replacement text is app-service-configurable which will be updated to add the "-" in the initial service key.


<a name="v1.0.0"></a>
## [v1.0.0] - 2019-11-11
### Bug
- **CommandClient:** Use proper API Route for Command Client
- **StoreForward:** Add missing retrieval of DB credentials from Vault

### Build
- **Attribution:** Add missing Attribution.txt file and update makefile test target
- **go.mod:** Add running go mod tidy to `make test`
- **makefile:** allow building in gopath by setting GO111MODULE=on

### Ci
- **VERSION:** Remove VERSION file

### Docs
- fix typo "rigistry" -> "registry" in README
- PR Template
- changelog information
- **contributing:** Document suggested format for commits
- **readme:** Address unknown type issue from getting started section
- **readme:** Updated sample code in readme
- **swagger:** add swagger annotations to generate spec from code
- **toc:** Adding a Table of Contents

### Feat
- **Context:** Add useful edgex clients to expose them for pipeline functions and internal use.
- **Filter:** Pass all events/reading through if no filter values are set
- **MqttSend:** Add SkipCertVerify setting and refactor MqttSend
- **appsdk:** Change configuration intervals to duration strings
- **appsdk:** Appsdk changes for Store and Forward.
- **configurable:** Expose MarkAsPushed
- **configuration:** Add overwrite option for force local settings into Registry
- **contracts:** Update to latest Core Contracts for new Command APIs
- **contracts:** Update to latest Core Contracts for new Command APIs
- **coredata:** Provide API to push to core-data
- **examples:** Add example to demonstrate using TargetType
- **mqtt:** Support to pass MQTT key/pair as byte array
- **profile:** Add environment override for profile command line argument
- **runtime:** Support types other than Event to be sent to function pipeline
- **runtime:** Store and Forward core implementation in runtime package.
- **store:** Redid Mongo integration tests.
- **store:** Updated to remove all indexing by ObjectID.
- **store:** Added contract validation and tests.
- **store:** add abstraction for StoredObject.
- **store:** Explicitly return values, fix missing imports on test.
- **store:** Address PR feedback.
- **store:** add mongo driver
- **store:** Refactored validateContract().
- **store:** Add mock inplementation for unit testing.
- **store:** Added Redis driver.
- **store:** Added error test cases.
- **transforms:** Add ability to persist data for later retry to export functions
- **version:** Validate that SDK's major version matches Core Service's major version
- **webserver:** Expose webserver to enable developer to add routes.
- **webserver:** Docs and tests for webserver use

### Feature
- **core-data:** MarkAsPushed is now available as a standalone function
- **version:** Add /api/version endpoint to SDK

### Fix
- **TargetType:** Make copy of target type before using it.
- **configuration:** Utilize protocol from [Service] configuration
- **configuration:** Check Interval is now respected
- **logging:** When trace is enabled, log message for topic subscription is correct
- **pushtocore:** error not returned to pipeline
- **trigger:** Return error to HTTP trigger response
- **webserver:** Timeout wasn't be used

### Perf
- **db.redis:** Denormalize AppServiceKey out of store object to optimize update

### Refactor
- Ensure test names are consistent with function names
- **examples:** Move examples out of SDK into new app-service-examples repo
- **sdk:** Refactor to use New func pattern instead of helper functions

### Style
- formatted code

### BREAKING CHANGE

/trigger endpoint now follows standard edgex convention. It is now /api/v1/trigger

HTTPPost and MQTTSend no longer automatically call MarkAsPushed upon success. It is upon the developer to ensure the method is called appropriately.

Pipeline functions used in the SetPipeline() now need to be created with the provided New…() functions.


<a name="v0.1.1"></a>
## [v0.1.1] - 2019-07-11
### Fix
- **log-filename:** filename specified in configuration.toml was not being respected


<a name="v0.1.0"></a>
## v0.1.0 - 2019-06-25

[Unreleased]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.43...HEAD
[v2.0.0-dev.43]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.42...v2.0.0-dev.43
[v2.0.0-dev.42]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.41...v2.0.0-dev.42
[v2.0.0-dev.41]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.40...v2.0.0-dev.41
[v2.0.0-dev.40]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.39...v2.0.0-dev.40
[v2.0.0-dev.39]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.38...v2.0.0-dev.39
[v2.0.0-dev.38]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.37...v2.0.0-dev.38
[v2.0.0-dev.37]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.36...v2.0.0-dev.37
[v2.0.0-dev.36]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.35...v2.0.0-dev.36
[v2.0.0-dev.35]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.34...v2.0.0-dev.35
[v2.0.0-dev.34]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.33...v2.0.0-dev.34
[v2.0.0-dev.33]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.32...v2.0.0-dev.33
[v2.0.0-dev.32]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.31...v2.0.0-dev.32
[v2.0.0-dev.31]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.30...v2.0.0-dev.31
[v2.0.0-dev.30]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.29...v2.0.0-dev.30
[v2.0.0-dev.29]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.28...v2.0.0-dev.29
[v2.0.0-dev.28]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.27...v2.0.0-dev.28
[v2.0.0-dev.27]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.26...v2.0.0-dev.27
[v2.0.0-dev.26]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.25...v2.0.0-dev.26
[v2.0.0-dev.25]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.24...v2.0.0-dev.25
[v2.0.0-dev.24]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.23...v2.0.0-dev.24
[v2.0.0-dev.23]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.22...v2.0.0-dev.23
[v2.0.0-dev.22]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.21...v2.0.0-dev.22
[v2.0.0-dev.21]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.20...v2.0.0-dev.21
[v2.0.0-dev.20]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.19...v2.0.0-dev.20
[v2.0.0-dev.19]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.18...v2.0.0-dev.19
[v2.0.0-dev.18]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.17...v2.0.0-dev.18
[v2.0.0-dev.17]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.16...v2.0.0-dev.17
[v2.0.0-dev.16]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.15...v2.0.0-dev.16
[v2.0.0-dev.15]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.14...v2.0.0-dev.15
[v2.0.0-dev.14]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.13...v2.0.0-dev.14
[v2.0.0-dev.13]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.12...v2.0.0-dev.13
[v2.0.0-dev.12]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.3.2-dev.1...v2.0.0-dev.12
[v1.3.2-dev.1]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.11...v1.3.2-dev.1
[v2.0.0-dev.11]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.10...v2.0.0-dev.11
[v2.0.0-dev.10]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.9...v2.0.0-dev.10
[v2.0.0-dev.9]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.3.1...v2.0.0-dev.9
[v1.3.1]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.8...v1.3.1
[v2.0.0-dev.8]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.3.1-dev.1...v2.0.0-dev.8
[v1.3.1-dev.1]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.7...v1.3.1-dev.1
[v2.0.0-dev.7]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.6...v2.0.0-dev.7
[v2.0.0-dev.6]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.5...v2.0.0-dev.6
[v2.0.0-dev.5]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.4...v2.0.0-dev.5
[v2.0.0-dev.4]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.3...v2.0.0-dev.4
[v2.0.0-dev.3]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.2...v2.0.0-dev.3
[v2.0.0-dev.2]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v2.0.0-dev.1...v2.0.0-dev.2
[v2.0.0-dev.1]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.3.0...v2.0.0-dev.1
[v1.3.0]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.2.0...v1.3.0
[v1.2.0]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v0.1.1...v1.0.0
[v0.1.1]: https://github.com/bill-mahoney/app-functions-sdk-go/compare/v0.1.0...v0.1.1
