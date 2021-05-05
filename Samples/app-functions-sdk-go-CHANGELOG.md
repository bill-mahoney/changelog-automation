<a name="unreleased"></a>
## [Unreleased]


<a name="x.y.z"></a>
## [x.y.z] - 2021-04-28
### Build
- Fix workflow for GitHub actions ([#789](https://github.com/edgexfoundry/app-functions-sdk-go/issues/789)) (#31d5382)
- Update to use go-mod-messaging v2 ([#638](https://github.com/edgexfoundry/app-functions-sdk-go/issues/638)) (#32260fc)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap/v2 ([#809](https://github.com/edgexfoundry/app-functions-sdk-go/issues/809)) (#366815e)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#806](https://github.com/edgexfoundry/app-functions-sdk-go/issues/806)) (#bacc8bd)
- **deps:** bump github.com/edgexfoundry/go-mod-registry/v2 ([#797](https://github.com/edgexfoundry/app-functions-sdk-go/issues/797)) (#8a711e4)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#800](https://github.com/edgexfoundry/app-functions-sdk-go/issues/800)) (#013d339)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap/v2 ([#798](https://github.com/edgexfoundry/app-functions-sdk-go/issues/798)) (#4d0ab09)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#788](https://github.com/edgexfoundry/app-functions-sdk-go/issues/788)) (#22e95e5)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#781](https://github.com/edgexfoundry/app-functions-sdk-go/issues/781)) (#1798f22)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#773](https://github.com/edgexfoundry/app-functions-sdk-go/issues/773)) (#60c5fe5)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap/v2 ([#762](https://github.com/edgexfoundry/app-functions-sdk-go/issues/762)) (#b297a99)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#757](https://github.com/edgexfoundry/app-functions-sdk-go/issues/757)) (#80a7af3)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging/v2 ([#715](https://github.com/edgexfoundry/app-functions-sdk-go/issues/715)) (#a1af34c)
- **deps:** bump github.com/stretchr/testify from 1.6.1 to 1.7.0 ([#636](https://github.com/edgexfoundry/app-functions-sdk-go/issues/636)) (#4921f11)
- **deps:** bump github.com/google/uuid from 1.1.4 to 1.1.5 ([#639](https://github.com/edgexfoundry/app-functions-sdk-go/issues/639)) (#bbd9394)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts/v2 ([#808](https://github.com/edgexfoundry/app-functions-sdk-go/issues/808)) (#a648416)
- **deps:** bump github.com/google/uuid from 1.1.2 to 1.1.4 ([#626](https://github.com/edgexfoundry/app-functions-sdk-go/issues/626)) (#2bc84c3)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#629](https://github.com/edgexfoundry/app-functions-sdk-go/issues/629)) (#3ba5abe)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#627](https://github.com/edgexfoundry/app-functions-sdk-go/issues/627)) (#5a165ca)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#628](https://github.com/edgexfoundry/app-functions-sdk-go/issues/628)) (#4055d1d)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#608](https://github.com/edgexfoundry/app-functions-sdk-go/issues/608)) (#d78c271)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets (#dbf2498)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap (#be0814d)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts (#148fdd2)

### Ci
- add code scanning (#805708f)
- standardize dockerfiles ([#610](https://github.com/edgexfoundry/app-functions-sdk-go/issues/610)) (#6d0fca7)

### Docs
- Add badges to readme (#ae6271d)

### Feat
- Remove MarkAsPushed feature ([#607](https://github.com/edgexfoundry/app-functions-sdk-go/issues/607)) (#c562d37)
- Add GetAppSetting convenience API ([#761](https://github.com/edgexfoundry/app-functions-sdk-go/issues/761)) (#7158bb1)
- Add custom structured configuration capability ([#753](https://github.com/edgexfoundry/app-functions-sdk-go/issues/753)) (#bc08826)
- Add new FilterBySourceName function ([#731](https://github.com/edgexfoundry/app-functions-sdk-go/issues/731)) (#3ee2f0b)
- Add secrets capability to Encryption pipeline function ([#706](https://github.com/edgexfoundry/app-functions-sdk-go/issues/706)) (#e84fe62)
- Port service template from hanoi branch ([#703](https://github.com/edgexfoundry/app-functions-sdk-go/issues/703)) (#ec0576e)
- Add debug logging of the Event Tags (#dfa455d)
- Update Filters for V2 DTO changes ([#680](https://github.com/edgexfoundry/app-functions-sdk-go/issues/680)) (#583298e)
- Add debug logging of Event/Reading details ([#666](https://github.com/edgexfoundry/app-functions-sdk-go/issues/666)) (#fc40647)
- Expect V2 Event DTO from triggers. ([#616](https://github.com/edgexfoundry/app-functions-sdk-go/issues/616)) (#2ceec0a)
- Remove deprecated MQTTSend pipeline function ([#592](https://github.com/edgexfoundry/app-functions-sdk-go/issues/592)) (#c9ed7d5)
- Allow for multiple MessageBus subscriptions ([#625](https://github.com/edgexfoundry/app-functions-sdk-go/issues/625)) (#b307360)
- Enable Registry and Config access token ([#772](https://github.com/edgexfoundry/app-functions-sdk-go/issues/772)) (#774021d)
- Remove remote logging service capability ([#585](https://github.com/edgexfoundry/app-functions-sdk-go/issues/585)) (#e5100d5)
- **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/edgexfoundry/app-functions-sdk-go/issues/587)) (#8220514)
- **sdk:** Add MakeItStop ([#613](https://github.com/edgexfoundry/app-functions-sdk-go/issues/613)) (#baae3ee)
- **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/edgexfoundry/app-functions-sdk-go/issues/644)) (#8142930)
- **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/edgexfoundry/app-functions-sdk-go/issues/589)) (#d5e638f)

### Fix
- Fix webserver to use ServerBindAddr only is not blank as rest of EdgeX Services ([#776](https://github.com/edgexfoundry/app-functions-sdk-go/issues/776)) (#1fb879a)
- Errors in dynamic pipeline updates allow previous pipeline to run, hiding the errors ([#711](https://github.com/edgexfoundry/app-functions-sdk-go/issues/711)) (#db11a9b)
- Return 400 (BadRequest) on DTO validation failure ([#710](https://github.com/edgexfoundry/app-functions-sdk-go/issues/710)) (#d1027b0)
- Fixed and enhanced Filter function debug messages ([#686](https://github.com/edgexfoundry/app-functions-sdk-go/issues/686)) (#b47a0ce)
- **sdk:** Normalize Trigger Factory Returns ([#699](https://github.com/edgexfoundry/app-functions-sdk-go/issues/699)) (#d22e914)
- **sdk:** Change default TargetType to be AddEventRequest ([#689](https://github.com/edgexfoundry/app-functions-sdk-go/issues/689)) (#771896a)
- **v2:** Expose Response Data ([#759](https://github.com/edgexfoundry/app-functions-sdk-go/issues/759)) (#2202295)

### Refactor
- Replace file based with use of Secret Provider to get Access Tokens ([#784](https://github.com/edgexfoundry/app-functions-sdk-go/issues/784)) (#c52b117)
- Switch to 2.0 Consul path ([#782](https://github.com/edgexfoundry/app-functions-sdk-go/issues/782)) (#da3d051)
- Update Version Check to use V2 endpoint ([#778](https://github.com/edgexfoundry/app-functions-sdk-go/issues/778)) (#a3b28f5)
- Update code for Created & Modified removed from Event DTO ([#771](https://github.com/edgexfoundry/app-functions-sdk-go/issues/771)) (#d683052)
- Use common SecretsRequest DTO from go-mod-core-contracts ([#622](https://github.com/edgexfoundry/app-functions-sdk-go/issues/622)) (#64c59fd)
- Change to using service keys for names in Clients configuration ([#747](https://github.com/edgexfoundry/app-functions-sdk-go/issues/747)) (#c6680ff)
- Adjust code for latest go-mod-core contracts changes ([#750](https://github.com/edgexfoundry/app-functions-sdk-go/issues/750)) (#f69f495)
- Remove unneeded call to validate CBOR encoded Event request ([#746](https://github.com/edgexfoundry/app-functions-sdk-go/issues/746)) (#8039246)
- Rework SDK to use Interfaces and factory methods ([#741](https://github.com/edgexfoundry/app-functions-sdk-go/issues/741)) (#3a57661)
- Remove V1 API code and swagger ([#730](https://github.com/edgexfoundry/app-functions-sdk-go/issues/730)) (#7e0294b)
- Consolidate function pipeline configuration ([#728](https://github.com/edgexfoundry/app-functions-sdk-go/issues/728)) (#4a1f060)
- Restructure Trigger configuration ([#724](https://github.com/edgexfoundry/app-functions-sdk-go/issues/724)) (#8767d03)
- Remove deprecated environment variables and related code ([#718](https://github.com/edgexfoundry/app-functions-sdk-go/issues/718)) (#866257f)
- Rename MqttBroker configuration to ExternalMqtt ([#717](https://github.com/edgexfoundry/app-functions-sdk-go/issues/717)) (#a6c3fef)
- Rework secrets for HTTP Export so value in InsecureSecrets can be overridden ([#714](https://github.com/edgexfoundry/app-functions-sdk-go/issues/714)) (#4075ac3)
- Update to latest modules and adjust code for changes ([#708](https://github.com/edgexfoundry/app-functions-sdk-go/issues/708)) (#1119998)
- Dynamically process either AddEventRequest DTO or Event DTO ([#693](https://github.com/edgexfoundry/app-functions-sdk-go/issues/693)) (#ebc40ac)
- Consume V2 version of edgex go-mods ([#649](https://github.com/edgexfoundry/app-functions-sdk-go/issues/649)) (#e76bbc7)
- Refactor V2 API /secrets to be singular /secret ([#648](https://github.com/edgexfoundry/app-functions-sdk-go/issues/648)) (#78327a4)
- Make SDK a V2 Go Module ([#643](https://github.com/edgexfoundry/app-functions-sdk-go/issues/643)) (#29611b3)
- Refactor to use new SecretProvider fro go-mod-bootstrap ([#604](https://github.com/edgexfoundry/app-functions-sdk-go/issues/604)) (#fb6bb54)
- **v2:** Update Custom Trigger Configuration ([#764](https://github.com/edgexfoundry/app-functions-sdk-go/issues/764)) (#ad2f1fe)

### BREAKING CHANGE

All App Services running with the secure Edgex Stack now need to have the SecretStore configured, a Vault token created and run with EDGEX_SECURITY_SECRET_STORE=true.

Consul configuration now under the `/2.0/` path

Webserver will be locked down to listen just to `Host` value when If `ServerBindAddr ` is blank

Clients configuration has changed and must be updated to use service keys for names

App Services will require refactoring to use new interfaces  and factory methods

V1 API's no longer supported

V1 API's no longer supported

- Renamed `Binding` to `Trigger`
- Removed deprecated `MessageBus` trigger type, replaced by`edgex-messagebus`
- Renamed `MessageBus` to `EdgexMessageBus`
- Move `EdgexMessageBus` and `ExternalMqtt` under `Trigger` configuration

The following environment variables no longer supported:
- `edgex_profile` (replaced by uppercase version)
- `edgex_service`

Configuration section name changed

Parameters have changed for HTTP Post/Put with SecretHeader


<a name="v1.3.1"></a>
## [v1.3.1] - 2021-02-04
### Fix
- Upgrade to go-mod-messaging with ZMQ fix ([#660](https://github.com/edgexfoundry/app-functions-sdk-go/issues/660)) (#eab384c)


<a name="v1.3.0"></a>
## [v1.3.0] - 2020-11-11
### Build
- Use latest go-mod-core-contracts and fix build errors due to name change ([#543](https://github.com/edgexfoundry/app-functions-sdk-go/issues/543)) (#fd3e27f)
- Switch to use Go 1.15 ([#478](https://github.com/edgexfoundry/app-functions-sdk-go/issues/478)) (#6f19a0c)
- Enable DependaBot via YML file, rather than external BOT (#030bce6)
- Enable DependaBot via YML file rather than external BOT (#a92b5c7)
- Enable DependaBot via YML file rather than external BOT (#379bc6b)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#566](https://github.com/edgexfoundry/app-functions-sdk-go/issues/566)) (#5b297c9)
- **deps:** bump github.com/edgexfoundry/go-mod-registry ([#558](https://github.com/edgexfoundry/app-functions-sdk-go/issues/558)) (#863bffa)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#559](https://github.com/edgexfoundry/app-functions-sdk-go/issues/559)) (#1d4da3c)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#545](https://github.com/edgexfoundry/app-functions-sdk-go/issues/545)) (#c65eb72)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#539](https://github.com/edgexfoundry/app-functions-sdk-go/issues/539)) (#95eebc9)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#562](https://github.com/edgexfoundry/app-functions-sdk-go/issues/562)) (#68e9754)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap (#4d6d34d)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#553](https://github.com/edgexfoundry/app-functions-sdk-go/issues/553)) (#6ed8672)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#564](https://github.com/edgexfoundry/app-functions-sdk-go/issues/564)) (#a92a438)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#563](https://github.com/edgexfoundry/app-functions-sdk-go/issues/563)) (#3bd4578)
- **deps:** bump github.com/google/uuid from 1.1.1 to 1.1.2 ([#458](https://github.com/edgexfoundry/app-functions-sdk-go/issues/458)) (#48a162b)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap ([#493](https://github.com/edgexfoundry/app-functions-sdk-go/issues/493)) (#fb86f14)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets ([#492](https://github.com/edgexfoundry/app-functions-sdk-go/issues/492)) (#fad33aa)
- **deps:** bump github.com/edgexfoundry/go-mod-messaging ([#496](https://github.com/edgexfoundry/app-functions-sdk-go/issues/496)) (#ffd58cb)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#565](https://github.com/edgexfoundry/app-functions-sdk-go/issues/565)) (#edbe35f)
- **deps:** bump github.com/gorilla/mux from 1.7.4 to 1.8.0 (#cf3e6f5)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#451](https://github.com/edgexfoundry/app-functions-sdk-go/issues/451)) (#0a27913)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts ([#447](https://github.com/edgexfoundry/app-functions-sdk-go/issues/447)) (#d0ad754)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts (#8372217)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts (#6a0b783)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap (#33e49c6)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap (#15d6b4a)
- **deps:** bump github.com/stretchr/testify from 1.5.1 to 1.6.1 (#ab903e7)
- **deps:** bump github.com/edgexfoundry/go-mod-core-contracts (#4fb16fc)
- **deps:** bump github.com/edgexfoundry/go-mod-bootstrap (#3477976)
- **deps:** bump github.com/edgexfoundry/go-mod-secrets (#41bd60e)

### Chore
- remove mongo DB implementation ([#399](https://github.com/edgexfoundry/app-functions-sdk-go/issues/399)) (#1c8db89)

### Ci
- update scopes and types for conventional commits ([#561](https://github.com/edgexfoundry/app-functions-sdk-go/issues/561)) (#07f5e21)
- update scope to include "deps" in semantic.yml (#6a1ce61)
- add scopes to pr-bot ([#411](https://github.com/edgexfoundry/app-functions-sdk-go/issues/411)) (#61ed54c)

### Docs
- addition of version and LTS refs to README per arch's meeting (#7a11604)
- update pr template to include dependencies question ([#382](https://github.com/edgexfoundry/app-functions-sdk-go/issues/382)) (#b5e0c58)

### Feat
- Add V2 Version endpoint ([#435](https://github.com/edgexfoundry/app-functions-sdk-go/issues/435)) (#6174217)
- add message bootstrap handler, fixes [#423](https://github.com/edgexfoundry/app-functions-sdk-go/issues/423) ([#424](https://github.com/edgexfoundry/app-functions-sdk-go/issues/424)) (#430b7bf)
- V2 Swagger Doc Design ([#422](https://github.com/edgexfoundry/app-functions-sdk-go/issues/422)) (#298ccb9)
- Implement V2 Ping endpoint and V2 layers ([#433](https://github.com/edgexfoundry/app-functions-sdk-go/issues/433)) (#1cb68c1)
- Implement transform to add Tags to Event ([#467](https://github.com/edgexfoundry/app-functions-sdk-go/issues/467)) (#c89ea64)
- Add logging of service version and total startup time ([#434](https://github.com/edgexfoundry/app-functions-sdk-go/issues/434)) (#ef90721)
- Implement V2 Secrets endpoint ([#441](https://github.com/edgexfoundry/app-functions-sdk-go/issues/441)) (#ffc77a0)
- Implement V2 Trigger endpoint ([#440](https://github.com/edgexfoundry/app-functions-sdk-go/issues/440)) (#b46b5c8)
- Implement V2 Config endpoint ([#437](https://github.com/edgexfoundry/app-functions-sdk-go/issues/437)) (#5783a75)
- Implement V2 Metrics endpoint ([#436](https://github.com/edgexfoundry/app-functions-sdk-go/issues/436)) (#9c4a1fd)
- Add ability to export via HTTP PUT with secret header support ([#546](https://github.com/edgexfoundry/app-functions-sdk-go/issues/546)) (#812c8b5)
- configurable ListenAndServe address, fixes [#405](https://github.com/edgexfoundry/app-functions-sdk-go/issues/405) ([#406](https://github.com/edgexfoundry/app-functions-sdk-go/issues/406)) (#e8b2565)
- **sdk:** Add background publisher to MessageBus ([#466](https://github.com/edgexfoundry/app-functions-sdk-go/issues/466)) (#7cb694d)
- **sdk:** expose RegistryClient on SDK ([#501](https://github.com/edgexfoundry/app-functions-sdk-go/issues/501)) (#3b3ebc9)
- **sdk:** Expose SDK EdgeX clients ([#525](https://github.com/edgexfoundry/app-functions-sdk-go/issues/525)) (#15f2541)
- **triggers:** Add MQTT Trigger with secure connection options ([#498](https://github.com/edgexfoundry/app-functions-sdk-go/issues/498)) (#f40e2be)

### Fix
- Fix response content type issue 567 ([#568](https://github.com/edgexfoundry/app-functions-sdk-go/issues/568)) (#a22ec22)
- http trigger response can set content-type ([#551](https://github.com/edgexfoundry/app-functions-sdk-go/issues/551)) (#d7502e4)
- Adjust timing so test doesn't fail intermittently ([#549](https://github.com/edgexfoundry/app-functions-sdk-go/issues/549)) (#529345a)
- backwards compatibility broken by [#406](https://github.com/edgexfoundry/app-functions-sdk-go/issues/406), fixes [#408](https://github.com/edgexfoundry/app-functions-sdk-go/issues/408) ([#409](https://github.com/edgexfoundry/app-functions-sdk-go/issues/409)) (#6ebb1d4)
- Set Redis password in MessageBus.Optional when using redisstreams ([#534](https://github.com/edgexfoundry/app-functions-sdk-go/issues/534)) (#7fa6067)
- Skip compatibility check when Core Data's version is 0.0.0 (developer build) ([#533](https://github.com/edgexfoundry/app-functions-sdk-go/issues/533)) (#35ab7bc)
- Make `path` property required for the Secrets V1 & V2 APIs ([#497](https://github.com/edgexfoundry/app-functions-sdk-go/issues/497)) (#a28a1e2)
- Data races detected from messagbus unit test [#488](https://github.com/edgexfoundry/app-functions-sdk-go/issues/488) ([#489](https://github.com/edgexfoundry/app-functions-sdk-go/issues/489)) (#c0b07c9)
- Fix  unit tests that fail when using Go 1.15 ([#485](https://github.com/edgexfoundry/app-functions-sdk-go/issues/485)) (#dd68bd8)
- Add locking around MQTT client setup and around connecting to avoid race conditions. ([#474](https://github.com/edgexfoundry/app-functions-sdk-go/issues/474)) (#b0f6186)
- Request DTO's RequestId is not required. Can be blank or a valid UUID ([#475](https://github.com/edgexfoundry/app-functions-sdk-go/issues/475)) (#3e706d9)
- Data races detected from Batch function [#448](https://github.com/edgexfoundry/app-functions-sdk-go/issues/448) ([#449](https://github.com/edgexfoundry/app-functions-sdk-go/issues/449)) (#337bfa7)
- Rename swagger file to use `yaml` extension. ([#465](https://github.com/edgexfoundry/app-functions-sdk-go/issues/465)) (#a75dd35)
- Trigger API schema type of `text` for errors is invalid, should be `string` ([#453](https://github.com/edgexfoundry/app-functions-sdk-go/issues/453)) (#6b45ea7)
- V2 Secrets return proper 201, 400 or 500 status codes, not 207. ([#443](https://github.com/edgexfoundry/app-functions-sdk-go/issues/443)) (#fc2196f)
- Allow startup duration/interval to be overridden via environement vars ([#426](https://github.com/edgexfoundry/app-functions-sdk-go/issues/426)) (#5d4b522)
- InsecureSecrets change processing should update SecretProvider.LastUpdated ([#420](https://github.com/edgexfoundry/app-functions-sdk-go/issues/420)) (#a9fe1e5)
- app-service-configurable issue 74 ([#383](https://github.com/edgexfoundry/app-functions-sdk-go/issues/383)) (#f08b8d6)
- **sdk:** Fix version check to handle new core-data `dev` versions. ([#416](https://github.com/edgexfoundry/app-functions-sdk-go/issues/416)) (#4847189)
- **triggers:** MQTT subscribe via onConnect handler so re-subscribe on reconnects ([#537](https://github.com/edgexfoundry/app-functions-sdk-go/issues/537)) (#c8e7ff0)

### Refactor
- Replace calling NewBaseResponseWithoutMessage with NewBaseResponse ([#557](https://github.com/edgexfoundry/app-functions-sdk-go/issues/557)) (#10e68ac)
- Change all unit tests to use logger.NewMockCient() ([#555](https://github.com/edgexfoundry/app-functions-sdk-go/issues/555)) (#02b6e43)
- Refactor V2 API to use new errors mechanism for go-mo-core-contracts ([#494](https://github.com/edgexfoundry/app-functions-sdk-go/issues/494)) (#e35ffeb)
- Remove Client monitoring. ([#386](https://github.com/edgexfoundry/app-functions-sdk-go/issues/386)) (#0aa127b)

### Revert
- **store-forward:** removal of Mongo implementation ([#414](https://github.com/edgexfoundry/app-functions-sdk-go/issues/414)) (#3c5d90b)


<a name="v1.2.0"></a>
## [v1.2.0] - 2020-06-11
### Docs
- update changelog ([#379](https://github.com/edgexfoundry/app-functions-sdk-go/issues/379)) (#0bed8a5)
- update changelog (#5b5af0e)

### Feat
- Add ability to Filter functions to reverse the logic to filter out specified names ([#375](https://github.com/edgexfoundry/app-functions-sdk-go/issues/375)) (#5ff514d)

### Fix
- fixed log message formatting ([#378](https://github.com/edgexfoundry/app-functions-sdk-go/issues/378)) (#97c757b)
- Allow overrides that have empty/blank value ([#374](https://github.com/edgexfoundry/app-functions-sdk-go/issues/374)) (#8418242)


<a name="v1.1.0"></a>
## [v1.1.0] - 2020-05-12
### Bug
- **README:** Fix example code in README to not panic if LoggingClient not initialized (#a7f6acd)
- **urlclient:** Update contracts version to fix bug in URLClient. (#a8ba403)

### Build
- Updated to latest go-mod-core-contract for bug fix ([#364](https://github.com/edgexfoundry/app-functions-sdk-go/issues/364)) (#aceb24c)
- Update relevant files in app-functions-sdk-go for Go 1.13. Close [#280](https://github.com/edgexfoundry/app-functions-sdk-go/issues/280) (#0123828)
- update go version to 1.13 (#b26dc8a)
- **Jenkinsfile:** Pipeline changes for Geneva release (#5de66a3)
- **go.mod:** update dependencies (#2da5c5e)

### Ci
- github actions experiment ([#366](https://github.com/edgexfoundry/app-functions-sdk-go/issues/366)) (#78b69fc)
- allow merge in git history (#62cc162)
- improve conventional commit conformance (#1f63c5f)
- **jenkins:** remove sandbox file (#531f52b)

### Docs
- update links to point to v1.2 (#d3c62bb)
- move docs to edgex-docs (#76095f3)
- adding batch to TOC (#9695d7b)
- batch documentation created (#2d51189)
- Update PR Template based on feedback (#b1a1b0b)
- Add webserver usage to ToC (#7ea3b5e)
- **pr-template:** remove contribution guidelines from PR checklist since commitlint checks this (#4321bad)

### Feat
- Add ability for command-line and environment override of service name ([#356](https://github.com/edgexfoundry/app-functions-sdk-go/issues/356)) (#dcb01ac)
- Integrate with new redis streams message bus implementation (#6fcbfc4)
- batch and send (#1a44398)
- **appsdk:** Add support for HTTPs on REST trigger (#b594893)
- **appsdk:** Add support for HTTPs on REST trigger (#b9ccbab)
- **bootstrap:** Integrate go-mod-bootstrap for common bootstraping (#1034e84)
- **configurable:** add JSONLogic (#e05bd13)
- **configurable:** add batch functions (#3ef7d39)
- **configurable:** add mqtt secret support (#d9433ed)
- **configurable:** support secrets for http export (#3358642)
- **core contracts:** Upgrade to latest Core Contracts for Reading enhancements (#a93dbb5)
- **http-export:** add support for auth token in header (#311414e)
- **jsonlogic:** add filter feature of jsonlogic (#9637eb0)
- **mqtt:** add security provider support for mqtt connection (#9695290)
- **sdk:** Implement StoreSecrets in app functions SDK (#1f7dc12)
- **sdk:** Add support for insecure secrets for when running non secure mode (#ad238fe)
- **sdk:** Add helper function to SDK to get string slice from App Settings. (#f83b325)
- **sdk:** Add full path to secrets api route (#9f72141)
- **security:** Add second SecurityStore client for service specific secrets (#204e3ef)

### Fix
- Remove code that returns empty credentials for Redis (#bd9dac5)
- Use correct parameter key name for MQTTSecretSend AuthMode in configurable pipeline ([#358](https://github.com/edgexfoundry/app-functions-sdk-go/issues/358)) (#b47159d)
- Implement smarter configuration update processing ([#354](https://github.com/edgexfoundry/app-functions-sdk-go/issues/354)) (#678d12a)
- Added longer sleep to fix intermittent unit test failure on ARM ([#352](https://github.com/edgexfoundry/app-functions-sdk-go/issues/352)) (#65b44ef)
- JSONLogic now runs rules everytime insted of 1st time (#e83dc16)
- Handle deprecated edgex_service env variable (#9e68ba5)
- Use credentials from Database config if not found in InsecureSecrets (#5c97927)
- Add more sleep time to Batch and Send unit test to fix ARM CI failures ([#361](https://github.com/edgexfoundry/app-functions-sdk-go/issues/361)) (#2c4cbff)
- **SecretClient:** Initialization of secret client retry logic (#ba62973)
- **SecurityProvider:** Make initialization of secret clients optional (#4b86353)
- **batch:** 2nd batch hanging in count mode (#3879fbb)
- **go.mod:** Removed wrong version of ZMQ package used. (#4bd3797)
- **profile:** Set profile properly in service's service key when env override used (#f6dd20a)
- **retry loop:** Wrap version check and DB connection is a retry loop instead of sending an error ([#345](https://github.com/edgexfoundry/app-functions-sdk-go/issues/345)) (#1bfa060)
- **trigger:** invoke connect on initialization (#b5a07d6)

### Refact
- **sdk:** Update usage of NewSecretClient to use the latest go-mod-secrets (#8b11b1f)

### Refactor
- Change serviceName override to be ServiceKey ([#365](https://github.com/edgexfoundry/app-functions-sdk-go/issues/365)) (#85cb718)
- Updated to use latest core-contracts changes (#7c6633a)
- **CBOR:** Replace ugorji/go with fixmacker/cbor (#93f855c)
- **sdk:** Add MQTT MessageBus Support (#9cc961e)
- **tests:** Fix order of expected vs actual and other clean up (#c0ff507)

### Test
- fix race condition in batch tests (#87f21c6)
- fix timing issue with Batch transform test (#701e960)

### BREAKING CHANGE

Inserting preceding "-" when replacing `<profile>` in the service key has been removed so the use is more flexible.  The only service using the <profile> replacement text is app-service-configurable which will be updated to add the "-" in the initial service key.


<a name="v1.0.0"></a>
## [v1.0.0] - 2019-11-11
### Bug
- **CommandClient:** Use proper API Route for Command Client (#b76f85c)
- **StoreForward:** Add missing retrieval of DB credentials from Vault (#e2e81ce)

### Build
- **Attribution:** Add missing Attribution.txt file and update makefile test target (#6f1a755)
- **go.mod:** Add running go mod tidy to `make test` (#d24fbcd)
- **makefile:** allow building in gopath by setting GO111MODULE=on (#d11277d)

### Ci
- **VERSION:** Remove VERSION file (#9d74176)

### Docs
- fix typo "rigistry" -> "registry" in README (#0cce673)
- PR Template (#ec47f61)
- changelog information (#75cbd94)
- **contributing:** Document suggested format for commits (#b264877)
- **readme:** Address unknown type issue from getting started section (#a6b9976)
- **readme:** Updated sample code in readme (#2fbe312)
- **swagger:** add swagger annotations to generate spec from code (#8e83cab)
- **toc:** Adding a Table of Contents (#08620d2)

### Feat
- **Context:** Add useful edgex clients to expose them for pipeline functions and internal use. (#29978f0)
- **Filter:** Pass all events/reading through if no filter values are set (#ad8e2ed)
- **MqttSend:** Add SkipCertVerify setting and refactor MqttSend (#2c25a52)
- **appsdk:** Change configuration intervals to duration strings (#e80ce9a)
- **appsdk:** Appsdk changes for Store and Forward. (#211efe4)
- **configurable:** Expose MarkAsPushed (#d86d0a0)
- **configuration:** Add overwrite option for force local settings into Registry (#7b6318d)
- **contracts:** Update to latest Core Contracts for new Command APIs (#7ef69f1)
- **contracts:** Update to latest Core Contracts for new Command APIs (#e818c23)
- **coredata:** Provide API to push to core-data (#d18e9d2)
- **examples:** Add example to demonstrate using TargetType (#1b9758f)
- **mqtt:** Support to pass MQTT key/pair as byte array (#985c91b)
- **profile:** Add environment override for profile command line argument (#c75d2ca)
- **runtime:** Support types other than Event to be sent to function pipeline (#ee6cf0e)
- **runtime:** Store and Forward core implementation in runtime package. (#1d28cc9)
- **store:** Redid Mongo integration tests. (#132f2fc)
- **store:** Updated to remove all indexing by ObjectID. (#01c114b)
- **store:** Added contract validation and tests. (#354adfb)
- **store:** add abstraction for StoredObject. (#b8d7b6a)
- **store:** Explicitly return values, fix missing imports on test. (#93fbaa2)
- **store:** Address PR feedback. (#8ab3aba)
- **store:** add mongo driver (#48f9171)
- **store:** Refactored validateContract(). (#50b0712)
- **store:** Add mock inplementation for unit testing. (#5cd4eaf)
- **store:** Added Redis driver. (#4f8ef02)
- **store:** Added error test cases. (#52e7605)
- **transforms:** Add ability to persist data for later retry to export functions (#351bbc2)
- **version:** Validate that SDK's major version matches Core Service's major version (#d91fdf1)
- **webserver:** Expose webserver to enable developer to add routes. (#e48170e)
- **webserver:** Docs and tests for webserver use (#3d5ac67)

### Feature
- **core-data:** MarkAsPushed is now available as a standalone function (#fdc4f0e)
- **version:** Add /api/version endpoint to SDK (#d9fdfd0)

### Fix
- **TargetType:** Make copy of target type before using it. (#069304b)
- **configuration:** Utilize protocol from [Service] configuration (#c6bec4a)
- **configuration:** Check Interval is now respected (#06a310f)
- **logging:** When trace is enabled, log message for topic subscription is correct (#ebe38a9)
- **pushtocore:** error not returned to pipeline (#61a3c1b)
- **trigger:** Return error to HTTP trigger response (#af60e79)
- **webserver:** Timeout wasn't be used (#df39230)

### Perf
- **db.redis:** Denormalize AppServiceKey out of store object to optimize update (#d065621)

### Refactor
- Ensure test names are consistent with function names (#b1e3b13)
- **examples:** Move examples out of SDK into new app-service-examples repo (#ed9e796)
- **sdk:** Refactor to use New func pattern instead of helper functions (#105f120)

### Style
- formatted code (#c6dcc18)

### BREAKING CHANGE

/trigger endpoint now follows standard edgex convention. It is now /api/v1/trigger

HTTPPost and MQTTSend no longer automatically call MarkAsPushed upon success. It is upon the developer to ensure the method is called appropriately.

Pipeline functions used in the SetPipeline() now need to be created with the provided New…() functions.


<a name="v0.1.1"></a>
## [v0.1.1] - 2019-07-11
### Fix
- **log-filename:** filename specified in configuration.toml was not being respected (#9007019)


<a name="v0.1.0"></a>
## v0.1.0 - 2019-06-25

[Unreleased]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/x.y.z...HEAD
[x.y.z]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v1.3.1...x.y.z
[v1.3.1]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v1.2.0...v1.3.0
[v1.2.0]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v0.1.1...v1.0.0
[v0.1.1]: https://github.com/edgexfoundry/app-functions-sdk-go/compare/v0.1.0...v0.1.1
