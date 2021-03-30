# Creates a function app and an Event Grid subscription

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/101-functions-eventgrid/CredScanResult.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)]("https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-functions-eventgrid%2Fazuredeploy.json")
[![Deploy To Azure US Gov](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.svg?sanitize=true)]("https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-functions-eventgrid%2Fazuredeploy.json")
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)]("http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-functions-eventgrid%2Fazuredeploy.json")

Creates an Event Grid topic and a subscription to an existing Azure function.

## Tasks performed by this template

This template performs the following tasks

* Creates an Event Grid custom topic
* Creates an Event Grid subscription that calls an existing Azure function Event Grid trigger

For more information about Azure Functions with Event Grid, see the [Azure Event Grid bindings for Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-event-grid/).
