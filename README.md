# Business AI Tutorials Overview
In this repository you can find exercises and information on different technologies of SAP's Business AI portfolio, including Generative AI Hub, SAP AI Services and Joule. 

On the [Business AI Sharepoint](https://sap.sharepoint.com/sites/208497) you can find more information.

On the **SAP Developer YouTube channel** you can find video tutorials for the Python SDK of GenAI Hub and the CAP-LLM-Plugin and more ([SAP AI YouTube playlist](https://www.youtube.com/playlist?list=PL6RpkC85SLQCDxe58RfZaLCcPqcgwTIhj)).
Also make sure signt up for **Devtoberfest** and check out the [Devtoberfest events calendar](https://community.sap.com/t5/devtoberfest/eb-p/devtoberfest-events).
We also have a lot of [SAP CodeJams](https://community.sap.com/t5/sap-codejam/gh-p/code-jam) with a lot of interessting topics!

## Exercise 1 - Prompt Engineering using SAP AI Launchpad and Generative AI Hub
With the [SAP AI Launchpad - Generative AI Hub Playground](https://sapit-core-playground-vole.ai-launchpad.prod.eu-central-1.aws.apps.ml.hana.ondemand.com/aic/index.html#/generativeaihub?workspace=sap-genai-xl&resourceGroup=default&/g/prompteditor) every employee can access all LLMs that are available through Generative AI Hub. Whatever SAP does or you want to do with LLMs should go through Generative AI Hub. This way we can ensure to comply with security standards.

In this CodeJam ([Generative AI CodeJam](https://github.com/SAP-samples/generative-ai-codejam/tree/main)) you can find everything you need to know about using the Python SDK of Generative AI Hub to implement a RAG use case with SAP HANA Cloud vector engine. Check out the second exercise ([prompt engineering using SAP AI Launchpad and Generative AI Hub](https://github.com/SAP-samples/generative-ai-codejam/blob/main/exercises/02-explore-genai-hub.md)) to learn about SAP AI Launchpad and prompt engineering.

On [https://www.promptingguide.ai/](https://www.promptingguide.ai/) you can find a lot more information on prompt engineering techniques.

## Exercise 2 - SAP AI Services - Document Information Extraction
Use Business Application Studio in your [Subaccount](https://emea.cockpit.btp.cloud.sap/cockpit/#/globalaccount/dfe5a086-f733-4955-8025-542e118e3e69/subaccount/8d188125-e96e-4e02-96d2-28e4b8606f06/service-instances) to implement the Python use cases unless you have Python installed on your machine or you can create a BAS subscription in your SAP BTP trial account.

With the SAP AI Service [Document Information Extraction (DOX)](https://help.sap.com/docs/document-information-extraction/document-information-extraction/what-is-document-information-extraction) you can extract information and fields from documents. Check out [this repository](https://github.com/noravth/may-developer-challenge-sap-ai-services/tree/main) to learn how to use the UI and the Python SDK.

## Exercise 3 - SAP AI Services - Data Attribute Recommendation
Another SAP AI Service is [Data Attribute Recommendation (DAR)](https://help.sap.com/docs/data-attribute-recommendation/data-attribute-recommendation/what-is-data-attribute-recommendation). Here you can find example code to train a regression model using DAR: [Data Attribute Recommendation - Training a regression model](https://www.community.sap.com/t5/application-development-discussions/may-developer-challenge-sap-ai-services-week-3/td-p/13701838)

## Exercise 4 - Joule
In this exercise you will learn how to implement a custom Joule capability. The example below adds a weather API to Joule. 

- First you need to create your password for Joule. Therefore, click on the Joule Application in BTP, say password forgotten and create a new password.
- Then you need to install the Joule CLI
[Install Joule CLI](https://help.sap.com/docs/joule/service-guide/install-and-update-command-line-interface)
- Here are more infos on Joule capabilities
[Infos on Joule](https://help.sap.com/docs/joule/joule-guide/build-capability?state=DRAFT&version=DEV)
- This is the exercise reporitory. You also need to clone the repository.
[Joule exercise repo](https://github.tools.sap/DAS-Samples/joule-functions-example/blob/main/tutorials/weather/index.md)
- To login to Joule run this command:
```sh
  joule login --apiurl 'add the Joule application url here' -a 'add the authentication url here'
         -c 'add the client id here' -s 'add the client secret here' -u 'your email' -p 'your password'
```
- [Only internal info on Joule architecture](https://github.tools.sap/CentralEngineering/TechnologyGuidelines/tree/main/tg24)
