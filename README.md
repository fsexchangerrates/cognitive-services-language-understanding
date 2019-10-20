---
page_type: sample
languages:
- csharp
- javascript
- html
- java
- python
products:
- azure
description: "LUIS allows your application to understand what a person wants in their own words."
urlFragment: cognitive-services-language-understanding
---

# Language Understanding (LUIS) Samples

Welcome to the Language Understanding ([LUIS](https://azure.microsoft.com/en-us/services/cognitive-services/language-understanding-intelligent-service/)) samples repository. LUIS allows your application to understand what a person wants in their own words. LUIS uses machine learning to allow developers to build applications that can receive user input in natural language and extract meaning from it.

## Create your Azure LUIS service

Use the `Deploy to Azure` button to quickly create an Azure LUIS service. You get one free LUIS service per account. The free service has a sku of `F0`. The basic tier has a sku of `S0`.

[![Create LUIS Service on Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

## Examples by language

|Example| CSharp | Java | Node.js | Javascript | Python | PHP | Ruby| JSON | GO |
| -- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|[Create and customize a LUIS app (Authoring)](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/LUIS/Authoring)|  ✔ | | ||||||
|Predict user utterances (Runtime)|  [REST](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/LUIS/Runtime), [SDK](./documentation-samples/sdk-quickstarts/c%23/UsePredictionRuntime)|REST |REST ||REST||||REST
|Build app programmatically |[REST](examples/build-app-programmatically-csv), [SDK](./documentation-samples/sdk-quickstarts/c%23/BuildModel) |  |✔|||||||
|[Upload utterances from query log](./examples/demo-upload-example-utterances/demo-Upload-utterances-from-querylog) | |  |✔|||||||
|[Upload utterances from exported app](./examples/demo-upload-example-utterances/demo-upload-utterances-from-exported-luis-app/) | |  |✔|||||||
|**[Quickstarts: Change model](./documentation-samples/quickstarts/change-model/)** | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) ||![Docker](./media/docker-logo.png)|
|**[Quickstarts: Analyze text](./documentation-samples/quickstarts/analyze-text/)** | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) | ![Docker](./media/docker-logo.png) ||![Docker](./media/docker-logo.png)|
|[Azure function to LUIS endpoint](./examples/azure-function-endpoint/) | ✔ |||||||||
|[Backup all apps in Subscription](./examples/backup/) | |  |✔|||||||
|[Add list entity](./documentation-samples/tutorial-list-entity/) | |  |✔|||||||
|[*Notes app sample ](./examples/notes-app/) | ✔  | | ![Docker](./media/docker-logo.png) ||||||
|[App model definition - Bookflight](./documentation-samples/Examples-BookFlight/) |||||||| ✔ ||
|[App model definition - Colors](./documentation-samples/Examples-Colors/) |||||||| ✔ ||
|[App model definition - IoT](./documentation-samples/examples-IoT) |||||||| ✔ ||
|[Phrase lists](./examples/phrase_list) | |  ||||||✔||
|[Bing Spell Check](./examples/bing-spell-check) | |  ||✔||||||
|[Azure function with application insights](./examples/azure-function-application-insights-endpoint) |✔ |  ||||||||
|[Download query log asynchronously](./examples/async-query-log/nodejs/)|||✔|||||||
|[Get region from app ID and subscription key](./documentation-samples/find-region/)|✔||✔|||||||
|[*Bot Integration sample - hotel finder](./bot-integration-samples/hotel-finder/) |  ✔ | | ✔ ||||||
|[Bot Integration sample - HomeAutomation](./documentation-samples/tutorial-web-app-bot) |  ✔ | | ✔ ||||||
|[Bot Integration sample - HomeAutomation & Application Insights](./documentation-samples/tutorial-web-app-bot-application-insights) | ✔  | | ✔ ||||||
|Bot Integration sample - <br>Study Bot - [Csharp](https://github.com/Azure-Samples/cognitive-services-studybot-csharp), [Node](https://github.com/Azure-Samples/cognitive-services-studybot-node) | ✔  | | ✔ ||||||

\* = example demonstrates complete cycle: create, train, publish, query

## Examples by usage

|Example|Demonstrates|
|--|--|
|[Create and customize a LUIS app (Authoring)](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/LUIS/Authoring) |Uses the LUIS SDK to create then customize an app |
|[Predict user utterances (Runtime)](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/LUIS/Runtime)| Uses the LUIS SDK to show utterance relevancy and intent scores |
|[Build app programmatically](examples/build-app-programmatically-csv) |Authoring API |
|[Upload utterances from query log](./examples/demo-upload-example-utterances/demo-Upload-utterances-from-querylog) |Authoring API |
|[Upload utterances from exported app](./examples/demo-upload-example-utterances/demo-upload-utterances-from-exported-luis-app/) |Authoring API |
|[Add an utterance to app model](./documentation-samples/authoring-api-samples/) |Authoring API |
|[Send utterance to endpoint](./documentation-samples/endpoint-api-samples/) |Endpoint API, Public app |
|[Azure function to LUIS endpoint](./examples/azure-function-endpoint/) |Endpoint API |
|[Backup all apps in Subscription](./examples/backup/) |Authoring API |
|[Notes app sample ](./examples/notes-app/) |Create-Train-Publish-Query, Prebuilt domain |
|[App model definition - Bookflight](./documentation-samples/Examples-BookFlight/) |Hierarchical entity, Composite entity, List entity, datetimeV2 prebuilt entity, number prebuilt entity, upload labeled utterance|
|[App model definition - Colors](./documentation-samples/Examples-Colors/) |Phrase list feature|
|[App model definition - IoT](./documentation-samples/examples-IoT) |Prebuilt domain|
|[Phrase lists](./examples/phrase_list) |Phrase list feature, Hierarchical entity, datetimeV2 prebuilt entity, number prebuilt entity |
|[Bing Spell Check](./examples/bing-spell-check) |Public App |
|[Azure function with application insights](./examples/azure-function-application-insights-endpoint) |Azure function, Application Insights |
|[Add list entity](./documentation-samples/tutorial-list-entity/) |List entity, train, query|
|[Download query log asynchronously](./examples/async-query-log/nodejs/)|Authoring API|
|[Bot Integration sample - hotel finder](./bot-integration-samples/hotel-finder/) |Bot Framework SDK, Create-Train-Publish-Query |
|[Bot Integration sample - HomeAutomation](./documentation-samples/tutorial-web-app-bot) |Web app bot |
|[Bot Integration sample - HomeAutomation & Application Insights](./documentation-samples/tutorial-web-app-bot-application-insights) |Web app bot, Application Insights |
|Bot Integration sample - <br>Study Bot - [Csharp](https://github.com/Azure-Samples/cognitive-services-studybot-csharp), [Node](https://github.com/Azure-Samples/cognitive-services-studybot-node) | Web app bot that integrates LUIS, QnA Maker, Bing Spell Check, and Speech Service |


## Interactive app
Ask LUIS to turn on the lights in this [interactive demonstration](https://azure.microsoft.com/en-us/services/cognitive-services/language-understanding-intelligent-service/).

## Healthbot

Tell the [Contoso Health bot](https://healthbotcontainer.azurewebsites.net/) where you are injured and the bot will recommend remedies.

## Intelligent Kiosk

The open-source [Intelligent Kiosk Sample](https://github.com/Microsoft/Cognitive-Samples-IntelligentKiosk) version is a collection of apps showcasing workflows and experiences built on top of the Microsoft Cognitive Services. Most of the experiences are hands-free and autonomous, using the human faces in front of a web camera as the main form of input (thus the word "kiosk" in the name).

Install the currently supported Intelligent Kiosk as a [Windows 10 app](https://aka.ms/kioskapp) and try out the various apps inside the kiosk, including apps with LUIS. 


## References
* [LUIS Docs](https://docs.microsoft.com/azure/cognitive-services/LUIS/)
* [FAQs](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-resources-faq), [Regions](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-reference-regions), [limits](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-boundaries), [Supported languages](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-supported-languages)

## APIs

last updated Oct 2019

Rest API ref docs

|Version|Type|By route|
|--|--|--|
|V3 stable|[Prediction](https://aka.ms/luis-apim-v3-prediction)||
|V3 preview|[Authoring](https://aka.ms/luis-apim-v3-authoring)|[Routes](#authoring-routes-v3-preview)|
|V2 stable|[Prediction](https://aka.ms/luis-endpoint-apis)||
|V2 stable|[Authoring](https://aka.ms/luis-authoring-apis)|[Routes](#authoring-routes-v2-stable)|

## SDKs 

last updated Feb 13, 2019

|Language|Package Manager|Samples|Reference Documentation|
|--|--|--|--|
|C#|  [NuGet - authoring](https://www.nuget.org/packages/Microsoft.Azure.CognitiveServices.Language.LUIS.Authoring/)<br>[NuGet - runtime](https://www.nuget.org/packages/Microsoft.Azure.CognitiveServices.Language.LUIS.Runtime/)|[Samples](https://github.com/Azure-Samples/cognitive-services-dotnet-sdk-samples/tree/master/LUIS)|[Docs](https://docs.microsoft.com/dotnet/api/overview/azure/cognitiveservices/client/languageunderstanding?view=azure-dotnet)|
|Go|[SDK - authoring](https://github.com/Azure/azure-sdk-for-go/tree/master/services/cognitiveservices/v2.0/luis/authoring)<br>[SDK - runtime](https://github.com/Azure/azure-sdk-for-go/tree/master/services/cognitiveservices/v2.0/luis/runtime)|-|[Docs](https://godoc.org/github.com/Azure/azure-sdk-for-go/services/cognitiveservices/v2.0/luis/)|
|Java|[Maven - authoring](https://search.maven.org/artifact/com.microsoft.azure.cognitiveservices/azure-cognitiveservices-luis-authoring)<br>[Maven - runtime](https://search.maven.org/artifact/com.microsoft.azure.cognitiveservices/azure-cognitiveservices-luis-runtime)|[Samples](https://github.com/Azure-Samples/cognitive-services-java-sdk-samples/tree/master/Language/LanguageUnderstanding)|[Docs](https://docs.microsoft.com/java/api/overview/azure/cognitiveservices/client/languageunderstanding?view=azure-java-stable)|
|Javascript|[NPM - authoring](https://www.npmjs.com/package/azure-cognitiveservices-luis-authoring)<br>[NPM - runtime](https://www.npmjs.com/package/azure-cognitiveservices-luis-runtime)|[Samples](https://github.com/Azure-Samples/cognitive-services-node-sdk-samples/tree/master/Samples/luis)||
|Python|[PIP](https://pypi.org/project/azure-cognitiveservices-language-luis/)|[Samples](https://github.com/Azure-Samples/cognitive-services-python-sdk-samples/tree/master/samples/language/luis)|[Docs](https://docs.microsoft.com/en-us/python/api/overview/azure/cognitiveservices/luis?view=azure-python)|
  
## Azure REST API
* [Autorest swagger](https://github.com/Azure/azure-rest-api-specs/tree/master/specification/cognitiveservices/data-plane/LUIS)
* [Full swagger](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/export?DocumentFormat=Swagger&ApiName=LUIS%20Programmatic%20APIs%20v2.0)



## Azure CLI
* [Cognitive Services](https://aka.ms/az-cli-cognitiveservices)

## Azure RM Powershell
* [Cognitive Services](https://aka.ms/azure-powershell-cognitiveservices)

## Common HTTP response codes
[Http codes](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-reference-response-codes)

## Bots
* [Bot Framework](https://docs.microsoft.com/bot-framework/)
* BotBuilder v4, [Nodejs](https://github.com/Microsoft/botbuilder-js), [.Net](https://github.com/Microsoft/botbuilder-dotnet). Coming soon: Python & Java
* BotBuilder v4 LUIS libraries: [Nodejs](https://www.npmjs.com/package/botframework-luis) NPM package, [.Net](https://www.nuget.org/packages/Microsoft.Bot.Builder.Ai/) NuGet package
* [Bot Builder Samples](https://github.com/Microsoft/BotBuilder-Samples)
* [Bot Builder Tools](https://github.com/Microsoft/botbuilder-tools)

## Related Services
* [QnA Maker](https://qnamaker.ai/)
* [Bing Speech API](https://azure.microsoft.com/services/cognitive-services/speech/)
* [Bing Spell Check API](https://azure.microsoft.com/services/cognitive-services/spell-check/)

## Dependencies
* [Recognizers-Text](https://github.com/Microsoft/Recognizers-Text) for prebuilt entities

## Azure status
[Regional availability](https://azure.microsoft.com/global-infrastructure/services/): LUIS is part of the AI and Machine Learning section.

## Videos

updated Dec 15, 2018

### Containers

[Video demonstration](https://azure.microsoft.com/en-us/resources/videos/language-understanding-container/) of [LUIS container](https://docs.microsoft.com/en-us/azure/cognitive-services/LUIS/luis-container-howto).

### //BUILD 2018
* [Azure Friday At Build 2018: Cognitive Services - Language (LUIS)](https://channel9.msdn.com/Shows/Azure-Friday/At-Build-2018-Cognitive-Services-Language-LUIS/player)
* [Build 2018 AI Show - What’s New with Language Understanding Service](https://channel9.msdn.com/Shows/AI-Show/Whats-New-with-Language-Understanding-Service-LUIS/player)
* [Build 2018 Session - Bot intelligence, Speech Capabilities, and NLU best practices](https://channel9.msdn.com/events/Build/2018/BRK3208)
* [Build 2018 - LUIS Updates](https://channel9.msdn.com/events/Build/2018/THR3118/player)

### Other videos
* [Introduction to LUIS](https://aka.ms/luis-intro-video)
* [Advanced learning with LUIS](https://www.youtube.com/watch?v=39L0Gv2EcSk)
* [Channel 9 Deep Dive into LUIS and Chatbots](https://channel9.msdn.com/Blogs/MVP-Azure/Cognitive-Services-Episode-3-Deep-dive-into-LUIS-and-Chatbots)
* [Conference Buddy Bot - AI Show](https://www.youtube.com/watch?v=LSlipMoz2vY)

## LUIS with Bot framework Blog
* [blog.botframework.com](https://blog.botframework.com/category/luis/)

## Courses including LUIS

* Mixed reality: [MR and Azure 303: Natural language understanding](https://docs.microsoft.com/windows/mixed-reality/mr-azure-303)

## Related Microsoft Projects

* [Prebuilt entity recognizer](https://github.com/Microsoft/Recognizers-Text)
* [Azure Code Samples for LUIS](https://azure.microsoft.com/resources/samples/?sort=0&term=Luis)
* [Universal Language Intelligence Service - Nodejs](https://github.com/Microsoft/Universal-Language-Intelligence-Service): A wrapper for the Microsoft LUIS cognitive that provides universal language support (after training) using the Bing Translate API
* [Microsoft Cognitive Services control for Microsoft Bot Builder - C# & Nodejs](https://github.com/Microsoft/BotBuilder-CognitiveServices): The cognitive services control makes consuming different Microsoft Cognitive Services easy for bots developed using Microsoft Bot Builder SDK. The control is available for C# and Node.js SDKs.
* [Activate Azure with Intelligent Apps - C#](https://github.com/Microsoft/intelligent-apps): Fabrikam Investment Bank Customer Service uses LUIS
* [LUIS Console Application Sample - C#](https://github.com/Azure-Samples/Cognitive-Services-LUIS-Console-Application)
* [Adaptive Cards](https://github.com/Microsoft/AdaptiveCards/)
* [Octobot from the Sandbox](https://docs.microsoft.com/sandbox/demos/octobot)
* [Microsoft Health Bot](https://docs.microsoft.com/healthbot/)

## Searching docs
* [Azure RSS for 'LUIS'](https://docs.microsoft.com/api/search/rss?search=LUIS&locale=en-us)

## Community Projects
If you find an open-source project or sample using LUIS, submit a PR for the [community-projects.md](community-projects.md) file.

## Prediction Routes v3 Stable

* /apps/{appId}/slots/{slotName}/predict  [[get](westus.dev.cognitive.microsoft.com/docs/services/luis-endpoint-api-v3-0/operations/Prediction_GetSlotPredictionGET),[post](westus.dev.cognitive.microsoft.com/docs/services/luis-endpoint-api-v3-0/operations/Prediction_GetSlotPrediction)]
* /apps/{appId}/versions/{versionId}/predict  [[get](westus.dev.cognitive.microsoft.com/docs/services/luis-endpoint-api-v3-0/operations/Prediction_GetVersionPredictionGET),[post](westus.dev.cognitive.microsoft.com/docs/services/luis-endpoint-api-v3-0/operations/Prediction_GetVersionPrediction)]

## Authoring Routes v3 Preview

* /apps/  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Add),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_List)]
* /apps/assistants  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListCortanaEndpoints)]
* /apps/cultures  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListSupportedCultures)]
* /apps/customprebuiltdomains  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListAvailableCustomPrebuiltDomains),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_AddCustomPrebuiltDomain)]
* /apps/customprebuiltdomains/{culture}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListAvailableCustomPrebuiltDomainsForCulture)]
* /apps/domains  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListDomains)]
* /apps/import  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Import)]
* /apps/usagescenarios  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListUsageScenarios)]
* /apps/{appId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Get),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Update),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Delete)]
* /apps/{appId}/azureaccounts  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/AzureAccounts_AssignToApp),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/AzureAccounts_GetAssigned),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/AzureAccounts_RemoveFromApp)]
* /apps/{appId}/endpoints  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_ListEndpoints)]
* /apps/{appId}/permissions  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Permissions_List),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Permissions_Add),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Permissions_Delete),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Permissions_Update)]
* /apps/{appId}/publish  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_Publish)]
* /apps/{appId}/publishsettings  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_GetPublishSettings),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_UpdatePublishSettings)]
* /apps/{appId}/querylogs  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_DownloadQueryLogs)]
* /apps/{appId}/settings  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_GetSettings),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_UpdateSettings)]
* /apps/{appId}/versions  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_List)]
* /apps/{appId}/versions/import  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Import)]
* /apps/{appId}/versions/{versionId}/  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Get),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Update),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Delete)]
* /apps/{appId}/versions/{versionId}/clone  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Clone)]
* /apps/{appId}/versions/{versionId}/closedlists  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListClosedLists),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddClosedList)]
* /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetClosedList),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateClosedList),[patch](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_PatchClosedList),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteClosedList)]
* /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}/sublists  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddSubList)]
* /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}/sublists/{subListId}  [[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteSubList),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateSubList)]
* /apps/{appId}/versions/{versionId}/closedlists/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListClosedListEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateClosedListEntityRole)]
* /apps/{appId}/versions/{versionId}/closedlists/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetClosedListEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateClosedListEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteClosedListEntityRole)]
* /apps/{appId}/versions/{versionId}/compositeentities  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCompositeEntities)]
* /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetCompositeEntity),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateCompositeEntity),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteCompositeEntity)]
* /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/children  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddCompositeEntityChild)]
* /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/children/{cChildId}  [[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteCompositeEntityChild)]
* /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCompositeEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateCompositeEntityRole)]
* /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetCompositeEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateCompositeEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteCompositeEntityRole)]
* /apps/{appId}/versions/{versionId}/customprebuiltdomains  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddCustomPrebuiltDomain)]
* /apps/{appId}/versions/{versionId}/customprebuiltdomains/{domainName}  [[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteCustomPrebuiltDomain)]
* /apps/{appId}/versions/{versionId}/customprebuiltentities  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddCustomPrebuiltEntity),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCustomPrebuiltEntities)]
* /apps/{appId}/versions/{versionId}/customprebuiltentities/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCustomPrebuiltEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateCustomPrebuiltEntityRole)]
* /apps/{appId}/versions/{versionId}/customprebuiltentities/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetCustomEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateCustomPrebuiltEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteCustomEntityRole)]
* /apps/{appId}/versions/{versionId}/customprebuiltintents  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddCustomPrebuiltIntent),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCustomPrebuiltIntents)]
* /apps/{appId}/versions/{versionId}/customprebuiltmodels  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListCustomPrebuiltModels)]
* /apps/{appId}/versions/{versionId}/entities  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddEntity),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListEntities)]
* /apps/{appId}/versions/{versionId}/entities/{entityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetEntity),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteEntity),[patch](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateEntityChild)]
* /apps/{appId}/versions/{versionId}/entities/{entityId}/children  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddEntityChild)]
* /apps/{appId}/versions/{versionId}/entities/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateEntityRole)]
* /apps/{appId}/versions/{versionId}/entities/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteEntityRole)]
* /apps/{appId}/versions/{versionId}/entities/{entityId}/suggest  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListEntitySuggestions)]
* /apps/{appId}/versions/{versionId}/example  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Examples_Add)]
* /apps/{appId}/versions/{versionId}/examples  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Examples_Batch),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Examples_List)]
* /apps/{appId}/versions/{versionId}/examples/{exampleId}  [[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Examples_Delete)]
* /apps/{appId}/versions/{versionId}/export  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_Export)]
* /apps/{appId}/versions/{versionId}/features  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_List)]
* /apps/{appId}/versions/{versionId}/hierarchicalentities  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListHierarchicalEntities)]
* /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetHierarchicalEntity),[patch](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateHierarchicalEntity),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteHierarchicalEntity)]
* /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/children/{hChildId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetHierarchicalEntityChild),[patch](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateHierarchicalEntityChild),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteHierarchicalEntityChild)]
* /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListHierarchicalEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateHierarchicalEntityRole)]
* /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetHierarchicalEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateHierarchicalEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteHierarchicalEntityRole)]
* /apps/{appId}/versions/{versionId}/intents  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddIntent),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListIntents)]
* /apps/{appId}/versions/{versionId}/intents/{intentId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetIntent),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateIntent),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteIntent)]
* /apps/{appId}/versions/{versionId}/intents/{intentId}/patternrules  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_ListIntentPatterns)]
* /apps/{appId}/versions/{versionId}/intents/{intentId}/suggest  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListIntentSuggestions)]
* /apps/{appId}/versions/{versionId}/listprebuilts  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListPrebuiltEntities)]
* /apps/{appId}/versions/{versionId}/models  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListModels)]
* /apps/{appId}/versions/{versionId}/models/{modelId}/examples  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_Examples)]
* /apps/{appId}/versions/{versionId}/patternanyentities  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListPatternAnyEntityInfos),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreatePatternAnyEntityModel)]
* /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetPatternAnyEntityInfo),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdatePatternAnyEntityModel),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeletePatternAnyEntityModel)]
* /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/explicitlist  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetExplicitList),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddExplicitListItem)]
* /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/explicitlist/{itemId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetExplicitListItem),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateExplicitListItem),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteExplicitListItem)]
* /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListPatternAnyEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreatePatternAnyEntityRole)]
* /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetPatternAnyEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdatePatternAnyEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeletePatternAnyEntityRole)]
* /apps/{appId}/versions/{versionId}/patternrule  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_AddPattern)]
* /apps/{appId}/versions/{versionId}/patternrules  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_ListPatterns),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_UpdatePatterns),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_BatchAddPatterns),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_DeletePatterns)]
* /apps/{appId}/versions/{versionId}/patternrules/{patternId}  [[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_UpdatePattern),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Pattern_DeletePattern)]
* /apps/{appId}/versions/{versionId}/patterns  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_CreatePatternFeature),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_ListApplicationVersionPatternFeatures)]
* /apps/{appId}/versions/{versionId}/patterns/{patternId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_GetPatternFeatureInfo),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_UpdatePatternFeature),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_DeletePatternFeature)]
* /apps/{appId}/versions/{versionId}/phraselists  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_AddPhraseList),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_ListPhraseLists)]
* /apps/{appId}/versions/{versionId}/phraselists/{phraselistId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_GetPhraseList),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_UpdatePhraseList),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Features_DeletePhraseList)]
* /apps/{appId}/versions/{versionId}/prebuilts  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_AddPrebuilt),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListPrebuilts)]
* /apps/{appId}/versions/{versionId}/prebuilts/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListPrebuiltEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreatePrebuiltEntityRole)]
* /apps/{appId}/versions/{versionId}/prebuilts/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetPrebuiltEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdatePrebuiltEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeletePrebuiltEntityRole)]
* /apps/{appId}/versions/{versionId}/prebuilts/{prebuiltId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetPrebuilt),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeletePrebuilt)]
* /apps/{appId}/versions/{versionId}/regexentities  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListRegexEntityInfos),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateRegexEntityModel)]
* /apps/{appId}/versions/{versionId}/regexentities/{entityId}/roles  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_ListRegexEntityRoles),[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_CreateRegexEntityRole)]
* /apps/{appId}/versions/{versionId}/regexentities/{entityId}/roles/{roleId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetRegexEntityRole),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateRegexEntityRole),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteRegexEntityRole)]
* /apps/{appId}/versions/{versionId}/regexentities/{regexEntityId}  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_GetRegexEntityEntityInfo),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_UpdateRegexEntityModel),[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Model_DeleteRegexEntityModel)]
* /apps/{appId}/versions/{versionId}/settings  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Settings_List),[put](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Settings_Update)]
* /apps/{appId}/versions/{versionId}/suggest  [[delete](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Versions_DeleteUnlabelledUtterance)]
* /apps/{appId}/versions/{versionId}/train  [[post](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Train_TrainVersion),[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Train_GetStatus)]
* /azureaccounts  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/AzureAccounts_ListUserLUISAccounts)]
* /package/{appId}/slot/{slotName}/gzip  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_PackagePublishedApplicationAsGzip)]
* /package/{appId}/versions/{versionId}/gzip  [[get](westeurope.dev.cognitive.microsoft.com/docs/services/luis-programmatic-apis-v3-0/operations/Apps_PackageTrainedApplicationAsGzip)]

## Authoring Routes v2 Stable

* /apps/  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2f),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c30)]
 * /apps/assistants  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c32)]
 * /apps/cultures  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c35)]
 * /apps/customprebuiltdomains  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104e515aca2f0b48c76be5),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104cec5aca2f0b48c76be3)]
 * /apps/customprebuiltdomains/{culture}  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104d855aca2f0b48c76be4)]
 * /apps/domains  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c33)]
 * /apps/import  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c31)]
 * /apps/usagescenarios  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c34)]
 * /apps/{appId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c39),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c37),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c38)]
 * **/apps/{appId}/azureaccounts**  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5be32228e8473de116325515),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5be32028a1d48f88cfd57e20),[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5be32554f8591db3a86232e1)]
 * /apps/{appId}/endpoints  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/590aff885aca2f09e404ec3f)]
 * /apps/{appId}/permissions  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58fcccdd5aca2f08a4104342),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58fccccd5aca2f08a4104341),[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58fcce195aca2f08a4104343),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58fcce825aca2f08a4104344)]
 * /apps/{appId}/publish  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3b)]
 * /apps/{appId}/publishsettings  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ae3212ed5b81c02cc64c6d2),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ae32174d5b81c02cc64c6d3)]
 * /apps/{appId}/querylogs/  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c36)]
 * /apps/{appId}/querylogsasync/  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ae02f7ed5b81c092c6cf2c3),[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ae02c03d5b81c092c6cf2c2)]
 * /apps/{appId}/settings  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58aef9fb39e2bb03dcd5909d),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58aeface39e2bb03dcd5909e)]
 * /apps/{appId}/versions  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3c)]
 * /apps/{appId}/versions/import  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5892283039e2bb0d9c2805f5)]
 * /apps/{appId}/versions/{versionId}/  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3f),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3d),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3e)]
 * /apps/{appId}/versions/{versionId}/assignedkey  [[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c42),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c41)]
 * /apps/{appId}/versions/{versionId}/clone  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c3a)]
 * /apps/{appId}/versions/{versionId}/closedlists  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c14),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c15)]
 * /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c29),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c26),[patch](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c28),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c27)]
 * /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}/sublists  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/590c5dc65aca2f04a0d3d684)]
 * /apps/{appId}/versions/{versionId}/closedlists/{clEntityId}/sublists/{subListId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2c),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59087d2d5aca2f03943a889a)]
 * /apps/{appId}/versions/{versionId}/closedlists/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade0d69d5b81c209ce2e59b),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade0d16d5b81c209ce2e59a)]
 * /apps/{appId}/versions/{versionId}/closedlists/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5c1ad5b81c209ce2e5b5),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5b29d5b81c209ce2e5b3),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5b5dd5b81c209ce2e5b4)]
 * /apps/{appId}/versions/{versionId}/compositeentities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c12),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c13)]
 * /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c25),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c23),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c24)]
 * /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/children  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/593889745aca2f0e24581850)]
 * /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/children/{cChildId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59388efb5aca2f0e24581853)]
 * /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade1315d5b81c209ce2e59f),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade12b3d5b81c209ce2e59e)]
 * /apps/{appId}/versions/{versionId}/compositeentities/{cEntityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade63c7d5b81c209ce2e5bb),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade6328d5b81c209ce2e5b9),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade636ad5b81c209ce2e5ba)]
 * /apps/{appId}/versions/{versionId}/customprebuiltdomains  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/591045b75aca2f0b48c76bdc)]
 * /apps/{appId}/versions/{versionId}/customprebuiltdomains/{domainName}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104b095aca2f0b48c76be2)]
 * /apps/{appId}/versions/{versionId}/customprebuiltentities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/591047bf5aca2f0b48c76bde),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104ab15aca2f0b48c76be1)]
 * /apps/{appId}/versions/{versionId}/customprebuiltentities/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5406d5b81c209ce2e5a7),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade52fad5b81c209ce2e5a6)]
 * /apps/{appId}/versions/{versionId}/customprebuiltentities/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade6622d5b81c209ce2e5c4),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade6581d5b81c209ce2e5c2),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade65aad5b81c209ce2e5c3)]
 * /apps/{appId}/versions/{versionId}/customprebuiltintents  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/591047175aca2f0b48c76bdd),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59104a525aca2f0b48c76be0)]
 * /apps/{appId}/versions/{versionId}/customprebuiltmodels  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/591049915aca2f0b48c76bdf)]
 * /apps/{appId}/versions/{versionId}/entities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0e),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0f)]
 * /apps/{appId}/versions/{versionId}/entities/{entityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1f),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1d),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1e)]
 * /apps/{appId}/versions/{versionId}/entities/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade084ad5b81c209ce2e597),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade082dd5b81c209ce2e596)]
 * /apps/{appId}/versions/{versionId}/entities/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5963d5b81c209ce2e5af),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5868d5b81c209ce2e5ad),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade58cfd5b81c209ce2e5ae)]
 * /apps/{appId}/versions/{versionId}/entities/{entityId}/suggest  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2e)]
 * /apps/{appId}/versions/{versionId}/example  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c08)]
 * /apps/{appId}/versions/{versionId}/examples  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c09),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0a)]
 * /apps/{appId}/versions/{versionId}/examples/{exampleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0b)]
 * /apps/{appId}/versions/{versionId}/export  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c40)]
 * /apps/{appId}/versions/{versionId}/externalKeys  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/589228f639e2bb0d9c2805f6),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c43)]
 * /apps/{appId}/versions/{versionId}/externalKeys/{keyType}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c44)]
 * /apps/{appId}/versions/{versionId}/features  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c01)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c10),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c11)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c22),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c20),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c21)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/children  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/593887c75aca2f0e2458184f)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/children/{hChildId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59388e185aca2f0e24581852),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/593884d65aca2f0e2458184e),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/59388c545aca2f0e24581851)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade52acd5b81c209ce2e5a5),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade526ad5b81c209ce2e5a4)]
 * /apps/{appId}/versions/{versionId}/hierarchicalentities/{hEntityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade654bd5b81c209ce2e5c1),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade64e1d5b81c209ce2e5bf),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade6515d5b81c209ce2e5c0)]
 * /apps/{appId}/versions/{versionId}/intents  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0c),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c0d)]
 * /apps/{appId}/versions/{versionId}/intents/{intentId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1c),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1a),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c1b)]
 * /apps/{appId}/versions/{versionId}/intents/{intentId}/patternrules  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf74d8d5b81c09bc0db028)]
 * /apps/{appId}/versions/{versionId}/intents/{intentId}/suggest  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2d)]
 * /apps/{appId}/versions/{versionId}/listprebuilts  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c18)]
 * /apps/{appId}/versions/{versionId}/models  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c19)]
 * /apps/{appId}/versions/{versionId}/patternanyentities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5101d5b81c209ce2e5a1),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade4f6bd5b81c209ce2e5a0)]
 * /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade575ed5b81c209ce2e5ac),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade55bdd5b81c209ce2e5aa),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade56a9d5b81c209ce2e5ab)]
 * /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/explicitlist  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade550bd5b81c209ce2e5a8),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5598d5b81c209ce2e5a9)]
 * /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/explicitlist/{itemId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade68d3d5b81c209ce2e5c7),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade6657d5b81c209ce2e5c5),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade676bd5b81c209ce2e5c6)]
 * /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5183d5b81c209ce2e5a3),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5137d5b81c209ce2e5a2)]
 * /apps/{appId}/versions/{versionId}/patternanyentities/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade64aed5b81c209ce2e5be),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade643bd5b81c209ce2e5bc),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade647bd5b81c209ce2e5bd)]
 * /apps/{appId}/versions/{versionId}/patternrule  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf41e9d5b81c09bc0db021)]
 * /apps/{appId}/versions/{versionId}/patternrules  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf4de4d5b81c09bc0db024),[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf72ebd5b81c09bc0db025),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf4a64d5b81c09bc0db022),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf4d1fd5b81c09bc0db023)]
 * /apps/{appId}/versions/{versionId}/patternrules/{patternId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf743ed5b81c09bc0db027),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5adf73bbd5b81c09bc0db026)]
 * /apps/{appId}/versions/{versionId}/patterns  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9bfd),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9bfe)]
 * /apps/{appId}/versions/{versionId}/patterns/{patternId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c04),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c02),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c03)]
 * /apps/{appId}/versions/{versionId}/phraselists  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9bff),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c00)]
 * /apps/{appId}/versions/{versionId}/phraselists/{phraselistId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c07),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c05),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c06)]
 * /apps/{appId}/versions/{versionId}/prebuilts  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c16),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c17)]
 * /apps/{appId}/versions/{versionId}/prebuilts/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade0c8bd5b81c209ce2e599),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade096cd5b81c209ce2e598)]
 * /apps/{appId}/versions/{versionId}/prebuilts/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5a8ad5b81c209ce2e5b2),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade59bcd5b81c209ce2e5b0),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade5a49d5b81c209ce2e5b1)]
 * /apps/{appId}/versions/{versionId}/prebuilts/{prebuiltId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2b),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c2a)]
 * /apps/{appId}/versions/{versionId}/regexentities  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5aa7d98cd5b81c0b702579e6),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5aa7dfd0d5b81c0b702579ea)]
 * /apps/{appId}/versions/{versionId}/regexentities/{entityId}/roles  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade0f32d5b81c209ce2e59d),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade0e74d5b81c209ce2e59c)]
 * /apps/{appId}/versions/{versionId}/regexentities/{entityId}/roles/{roleId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade61f2d5b81c209ce2e5b8),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade602bd5b81c209ce2e5b6),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5ade606dd5b81c209ce2e5b7)]
 * /apps/{appId}/versions/{versionId}/regexentities/{regexEntityId}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5aa7db53d5b81c0b702579e8),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5aa7dd5cd5b81c0b702579e9),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5aa7e16cd5b81c0b702579eb)]
 * /apps/{appId}/versions/{versionId}/settings  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/versions-get-application-version-settings),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/versions-update-application-version-settings)]
 * /apps/{appId}/versions/{versionId}/suggest  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58b6f32139e2bb139ce823c9)]
 * /apps/{appId}/versions/{versionId}/train  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c46),[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c45)]
 * **/azureaccounts**  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5be313cec181ae720aa2b26c)]
 * /externalKeys  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c49),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c4a)]
 * /externalKeys/{externalKeyValue}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c4d)]
 * /package/{appId}/slot/{slotName}/gzip  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/apps-packagepublishedapplicationasgzip)]
 * /package/{appId}/versions/{versionId}/gzip  [[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/apps-packagetrainedapplicationasgzip)]
 * /programmatickey  [[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c4b)]
 * /subscriptions  [[post](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c47),[get](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c48),[put](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/58b6f1a639e2bb139ce823c8)]
 * /subscriptions/{subscriptionKey}  [[delete](https://westus.dev.cognitive.microsoft.com/docs/services/5890b47c39e2bb17b84a55ff/operations/5890b47c39e2bb052c5b9c4c)]


Route map generated with [swagger-tools](https://github.com/diberry/swagger-tools/blob/master/swagger-to-route-with-verbs-linked-to-apim-docs.js).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

