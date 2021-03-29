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

This template creates a function app and sets up an Event Grid subscription to call the function when a VM write happens in Azure.

## Tasks performed by this template

This template performs the following tasks

* Creates a storage account to store the functions code.
* Creates an application insights resource to store logs and metrics for the function.
* Creates a functions application with with an Event Grid subscription running on a consumption plan.

For more information about Azure Functions, see the [Azure Functions Overview](https://azure.microsoft.com/en-us/documentation/articles/functions-overview/).
