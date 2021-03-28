# Preparation
Follow these steps to get started before the lecture

### Azure subscription
* Get yourself a [free azure subscription](https://azure.microsoft.com/en-us/free/students/) or sign into the subscription provided by the university.
* You should be able to login to the [Azure portal](https://portal.azure.com/#home) once you have access.
![image](https://user-images.githubusercontent.com/1269880/110250216-29c3c200-7f48-11eb-9318-b5ed9a7af717.png)

### Azure machine learing workspace
AzureML workspace is a central repository of all your machine learning assets including code, models, compute resources and previously executed runs and experiments. In order to start using Azure Machine Learning, you will need to create an Azure Machine Learning workspace. You can do this programmatically in [python](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace?tabs=python) or through the [Azure portal(recommended)](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace?tabs=azure-portal)

#### Create a new workspace
This will take you to a resource creation dialog similar to the one below
<img src=https://docs.microsoft.com/en-us/azure/machine-learning/media/how-to-manage-workspace/create-workspace.gif>
You can select an existing resource group or create a new resource group to hold the AzureML workspace. The workspace uses other azure resource such as storage, key vault, application insight and container registry. You can chose to reuse existing resources by selecting it or create new resources. 
![image](https://user-images.githubusercontent.com/1269880/110253140-c1301180-7f56-11eb-96a1-aab3c242b8be.png)
