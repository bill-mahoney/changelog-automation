# [2.0.0](https://github.com/bill-mahoney/app-functions-sdk-go/compare/v1.3.0...v2.0.0) (2021-04-10)


### Bug Fixes

* Fix webserver to use ServerBindAddr only is not blank as rest of EdgeX Services ([#776](https://github.com/bill-mahoney/app-functions-sdk-go/issues/776)) ([1fb879a](https://github.com/bill-mahoney/app-functions-sdk-go/commit/1fb879a)), closes [#775](https://github.com/bill-mahoney/app-functions-sdk-go/issues/775)
* **v2:** Expose Response Data ([#759](https://github.com/bill-mahoney/app-functions-sdk-go/issues/759)) ([2202295](https://github.com/bill-mahoney/app-functions-sdk-go/commit/2202295))
* Errors in dynamic pipeline updates allow previous pipeline to run, hiding the errors ([#711](https://github.com/bill-mahoney/app-functions-sdk-go/issues/711)) ([db11a9b](https://github.com/bill-mahoney/app-functions-sdk-go/commit/db11a9b)), closes [#707](https://github.com/bill-mahoney/app-functions-sdk-go/issues/707)
* Fixed and enhanced Filter function debug messages ([#686](https://github.com/bill-mahoney/app-functions-sdk-go/issues/686)) ([b47a0ce](https://github.com/bill-mahoney/app-functions-sdk-go/commit/b47a0ce)), closes [#685](https://github.com/bill-mahoney/app-functions-sdk-go/issues/685)
* Return 400 (BadRequest) on DTO validation failure ([#710](https://github.com/bill-mahoney/app-functions-sdk-go/issues/710)) ([d1027b0](https://github.com/bill-mahoney/app-functions-sdk-go/commit/d1027b0)), closes [#702](https://github.com/bill-mahoney/app-functions-sdk-go/issues/702)
* **sdk:** Change default TargetType to be AddEventRequest ([#689](https://github.com/bill-mahoney/app-functions-sdk-go/issues/689)) ([771896a](https://github.com/bill-mahoney/app-functions-sdk-go/commit/771896a)), closes [#688](https://github.com/bill-mahoney/app-functions-sdk-go/issues/688)
* **sdk:** Normalize Trigger Factory Returns ([#699](https://github.com/bill-mahoney/app-functions-sdk-go/issues/699)) ([d22e914](https://github.com/bill-mahoney/app-functions-sdk-go/commit/d22e914))


### Code Refactoring

* Change to using service keys for names in Clients configuration ([#747](https://github.com/bill-mahoney/app-functions-sdk-go/issues/747)) ([c6680ff](https://github.com/bill-mahoney/app-functions-sdk-go/commit/c6680ff)), closes [#739](https://github.com/bill-mahoney/app-functions-sdk-go/issues/739)
* Remove deprecated environment variables and related code ([#718](https://github.com/bill-mahoney/app-functions-sdk-go/issues/718)) ([866257f](https://github.com/bill-mahoney/app-functions-sdk-go/commit/866257f)), closes [#337](https://github.com/bill-mahoney/app-functions-sdk-go/issues/337)
* Remove V1 API code and swagger ([#730](https://github.com/bill-mahoney/app-functions-sdk-go/issues/730)) ([7e0294b](https://github.com/bill-mahoney/app-functions-sdk-go/commit/7e0294b)), closes [#720](https://github.com/bill-mahoney/app-functions-sdk-go/issues/720)
* Rename MqttBroker configuration to ExternalMqtt ([#717](https://github.com/bill-mahoney/app-functions-sdk-go/issues/717)) ([a6c3fef](https://github.com/bill-mahoney/app-functions-sdk-go/commit/a6c3fef)), closes [#673](https://github.com/bill-mahoney/app-functions-sdk-go/issues/673)
* Replace file based with use of Secret Provider to get Access Tokens ([#784](https://github.com/bill-mahoney/app-functions-sdk-go/issues/784)) ([c52b117](https://github.com/bill-mahoney/app-functions-sdk-go/commit/c52b117)), closes [#769](https://github.com/bill-mahoney/app-functions-sdk-go/issues/769)
* Restructure Trigger configuration ([#724](https://github.com/bill-mahoney/app-functions-sdk-go/issues/724)) ([8767d03](https://github.com/bill-mahoney/app-functions-sdk-go/commit/8767d03)), closes [#719](https://github.com/bill-mahoney/app-functions-sdk-go/issues/719) [#655](https://github.com/bill-mahoney/app-functions-sdk-go/issues/655)
* Rework SDK to use Interfaces and factory methods ([#741](https://github.com/bill-mahoney/app-functions-sdk-go/issues/741)) ([3a57661](https://github.com/bill-mahoney/app-functions-sdk-go/commit/3a57661)), closes [#573](https://github.com/bill-mahoney/app-functions-sdk-go/issues/573)
* Rework secrets for HTTP Export so value in InsecureSecrets can be overridden ([#714](https://github.com/bill-mahoney/app-functions-sdk-go/issues/714)) ([4075ac3](https://github.com/bill-mahoney/app-functions-sdk-go/commit/4075ac3)), closes [#521](https://github.com/bill-mahoney/app-functions-sdk-go/issues/521)
* Switch to 2.0 Consul path ([#782](https://github.com/bill-mahoney/app-functions-sdk-go/issues/782)) ([da3d051](https://github.com/bill-mahoney/app-functions-sdk-go/commit/da3d051)), closes [#768](https://github.com/bill-mahoney/app-functions-sdk-go/issues/768)


### Features

* Add custom structured configuration capability ([#753](https://github.com/bill-mahoney/app-functions-sdk-go/issues/753)) ([bc08826](https://github.com/bill-mahoney/app-functions-sdk-go/commit/bc08826)), closes [#557](https://github.com/bill-mahoney/app-functions-sdk-go/issues/557) [#578](https://github.com/bill-mahoney/app-functions-sdk-go/issues/578)
* Add debug logging of Event/Reading details ([#666](https://github.com/bill-mahoney/app-functions-sdk-go/issues/666)) ([fc40647](https://github.com/bill-mahoney/app-functions-sdk-go/commit/fc40647)), closes [#665](https://github.com/bill-mahoney/app-functions-sdk-go/issues/665)
* Add debug logging of the Event Tags ([dfa455d](https://github.com/bill-mahoney/app-functions-sdk-go/commit/dfa455d)), closes [#700](https://github.com/bill-mahoney/app-functions-sdk-go/issues/700)
* Add GetAppSetting convenience API ([#761](https://github.com/bill-mahoney/app-functions-sdk-go/issues/761)) ([7158bb1](https://github.com/bill-mahoney/app-functions-sdk-go/commit/7158bb1)), closes [#760](https://github.com/bill-mahoney/app-functions-sdk-go/issues/760)
* Add new FilterBySourceName function ([#731](https://github.com/bill-mahoney/app-functions-sdk-go/issues/731)) ([3ee2f0b](https://github.com/bill-mahoney/app-functions-sdk-go/commit/3ee2f0b)), closes [#720](https://github.com/bill-mahoney/app-functions-sdk-go/issues/720)
* Add secrets capability to Encryption pipeline function ([#706](https://github.com/bill-mahoney/app-functions-sdk-go/issues/706)) ([e84fe62](https://github.com/bill-mahoney/app-functions-sdk-go/commit/e84fe62)), closes [#372](https://github.com/bill-mahoney/app-functions-sdk-go/issues/372)
* Allow for multiple MessageBus subscriptions ([#625](https://github.com/bill-mahoney/app-functions-sdk-go/issues/625)) ([b307360](https://github.com/bill-mahoney/app-functions-sdk-go/commit/b307360)), closes [#596](https://github.com/bill-mahoney/app-functions-sdk-go/issues/596)
* Enable Registry and Config access token ([#772](https://github.com/bill-mahoney/app-functions-sdk-go/issues/772)) ([774021d](https://github.com/bill-mahoney/app-functions-sdk-go/commit/774021d)), closes [#769](https://github.com/bill-mahoney/app-functions-sdk-go/issues/769)
* Expect V2 Event DTO from triggers. ([#616](https://github.com/bill-mahoney/app-functions-sdk-go/issues/616)) ([2ceec0a](https://github.com/bill-mahoney/app-functions-sdk-go/commit/2ceec0a)), closes [#595](https://github.com/bill-mahoney/app-functions-sdk-go/issues/595)
* Port service template from hanoi branch ([#703](https://github.com/bill-mahoney/app-functions-sdk-go/issues/703)) ([ec0576e](https://github.com/bill-mahoney/app-functions-sdk-go/commit/ec0576e)), closes [#674](https://github.com/bill-mahoney/app-functions-sdk-go/issues/674)
* Update Filters for V2 DTO changes ([#680](https://github.com/bill-mahoney/app-functions-sdk-go/issues/680)) ([583298e](https://github.com/bill-mahoney/app-functions-sdk-go/commit/583298e)), closes [#653](https://github.com/bill-mahoney/app-functions-sdk-go/issues/653) [#654](https://github.com/bill-mahoney/app-functions-sdk-go/issues/654)
* **sdk:** Add MakeItStop ([#613](https://github.com/bill-mahoney/app-functions-sdk-go/issues/613)) ([baae3ee](https://github.com/bill-mahoney/app-functions-sdk-go/commit/baae3ee))
* **sdk:** Enable Custom Trigger Registration ([#587](https://github.com/bill-mahoney/app-functions-sdk-go/issues/587)) ([8220514](https://github.com/bill-mahoney/app-functions-sdk-go/commit/8220514)), closes [#586](https://github.com/bill-mahoney/app-functions-sdk-go/issues/586)
* **sdk:** Use ResponseContentType in MessageBus ([#644](https://github.com/bill-mahoney/app-functions-sdk-go/issues/644)) ([8142930](https://github.com/bill-mahoney/app-functions-sdk-go/commit/8142930))
* Remove deprecated MQTTSend pipeline function ([#592](https://github.com/bill-mahoney/app-functions-sdk-go/issues/592)) ([c9ed7d5](https://github.com/bill-mahoney/app-functions-sdk-go/commit/c9ed7d5)), closes [#547](https://github.com/bill-mahoney/app-functions-sdk-go/issues/547)
* Remove MarkAsPushed feature ([#607](https://github.com/bill-mahoney/app-functions-sdk-go/issues/607)) ([c562d37](https://github.com/bill-mahoney/app-functions-sdk-go/commit/c562d37)), closes [#594](https://github.com/bill-mahoney/app-functions-sdk-go/issues/594)
* **store-forward:** Remove Mongo as supported DB option ([#589](https://github.com/bill-mahoney/app-functions-sdk-go/issues/589)) ([d5e638f](https://github.com/bill-mahoney/app-functions-sdk-go/commit/d5e638f)), closes [#395](https://github.com/bill-mahoney/app-functions-sdk-go/issues/395)
* Remove remote logging service capability ([#585](https://github.com/bill-mahoney/app-functions-sdk-go/issues/585)) ([e5100d5](https://github.com/bill-mahoney/app-functions-sdk-go/commit/e5100d5)), closes [#396](https://github.com/bill-mahoney/app-functions-sdk-go/issues/396)


### BREAKING CHANGES

* All App Services running with the secure Edgex Stack now need to have the SecretStore configured, a Vault token created and run with EDGEX_SECURITY_SECRET_STORE=true.

Signed-off-by: lenny <leonard.goodell@intel.com>
* Consul configuration now under the `/2.0/` path

Signed-off-by: lenny <leonard.goodell@intel.com>
* Webserver will be locked down to listen just to `Host` value when If `ServerBindAddr ` is blank

Signed-off-by: lenny <leonard.goodell@intel.com>
* Clients configuration has changed and must be updated to use service keys for names

Signed-off-by: lenny <leonard.goodell@intel.com>
* App Services will require refactoring to use new interfaces  and factory methods

Signed-off-by: lenny <leonard.goodell@intel.com>
* V1 API's no longer supported

Signed-off-by: lenny <leonard.goodell@intel.com>
* V1 API's no longer supported

Signed-off-by: lenny <leonard.goodell@intel.com>
* - Renamed `Binding` to `Trigger`
- Removed deprecated `MessageBus` trigger type, replaced by`edgex-messagebus`
- Renamed `MessageBus` to `EdgexMessageBus`
- Move `EdgexMessageBus` and `ExternalMqtt` under `Trigger` configuration

Signed-off-by: lenny <leonard.goodell@intel.com>
* The following environment variables no longer supported:
- `edgex_profile` (replaced by uppercase version)
- `edgex_service`

Signed-off-by: lenny <leonard.goodell@intel.com>
* Configuration section name changed

Signed-off-by: lenny <leonard.goodell@intel.com>
* Parameters have changed for HTTP Post/Put with SecretHeader

Signed-off-by: lenny <leonard.goodell@intel.com>
