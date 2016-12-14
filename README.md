# AnomalyDetection-API

[![Deploy to Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png)](http://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAnomalyDetection-API%2Fmaster%2Fazuredeploy.json)

# Deployment Instructions
1. Click the "Deploy to Azure" button above
2. You will be required to chose a Resource Group name and a location where the resources will be deployed.
3. Once the deployment completes, you will be able to find the Resource Group in the [Azure Portal](https://ms.portal.azure.com/#blade/HubsExtension/Resources/resourceType/Microsoft.Resources%2Fsubscriptions%2FresourceGroups)
4. You can manage the web services from the [Azure ML Web Services page](https://services.azureml.net/webservices/).  From here you can test the endpoints, find the API keys, read documentation, etc.  Detailed instructions are availabe [here](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-manage-new-webservice)

# Scaling the API
This template will deploy a free Dev/Test billing plan.  You may wish to upgrade to larger plan.  Details on the pricing and compute resources of different plans are available [here](https://azure.microsoft.com/en-us/pricing/details/machine-learning/) under "Production Web API pricing".

You can manage your billing plan [here](https://services.azureml.net/plans/).  Instructions on how to upgrade your plan are available [here](https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-manage-new-webservice) under the "Manage New Web services" section.
