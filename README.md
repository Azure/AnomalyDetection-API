# AnomalyDetection-API

[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png)](http://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAnomalyDetection-API%2Fmaster%2Fazuredeploy.json)

# Introduction
The Anomaly Detection API can help identify anomalous data points in time series data (more details [here](https://gallery.cortanaintelligence.com/MachineLearningAPI/Anomaly-Detection-2)).  This repository contains an [ARM template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview) that will deploy the API to your Azure subscription as an [Azure Machine Learning Web Service](https://services.azureml.net/).

# Deployment Instructions
1. Click the "Deploy to Azure" button above
2. You will be required to choose a resource group name and a region where the API resources will be deployed.  You will also be able to choose a billing plan for the AzureML web services that will be deployed.  *Note that you are only allowed **one DevTest plan per Azure subscription**.  If you already have a DevTest plan, you must chose a higher tier*.
3. Once the deployment completes, you will be able to find the Resource Group in the [Azure Portal](https://ms.portal.azure.com/#blade/HubsExtension/Resources/resourceType/Microsoft.Resources%2Fsubscriptions%2FresourceGroups).  The names of the resources will be based on the resource group name provided in step 2.
4. You can manage the web services from the [Azure ML Web Services page](https://services.azureml.net/webservices/).  From here you can test the endpoints, find the API keys, read documentation, etc. Detailed instructions are availabe [here](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-manage-new-webservice)

# Scaling the API
This template will deploy a free Dev/Test billing plan by default.  You can upgrade to another plan based on your needs.  Details on the pricing and compute resources of different plans are available [here](https://azure.microsoft.com/en-us/pricing/details/machine-learning/) under "Production Web API pricing".

## Managing AML Plans 
You can manage your billing plan [here](https://services.azureml.net/plans/).  The plan name will be based on the resource group name you chose when deploying the API, plus a string that is unique to your subscription.  Instructions on how to upgrade your plan are available [here](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-manage-new-webservice) under the "Managing billing plans" section.

# Contact
If you have any further issues or questions, please [email us](mailto:admlsupport@microsoft.com).
