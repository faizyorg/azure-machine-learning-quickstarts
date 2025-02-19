# Setting up your environment 

If a lab environment has not be provided for you, this quickstart provides the instructions to get started in your own Azure Subscription.

The following summarizes the requirements when you want to setup your own environment (for example, on your local machine). If this is your first time performing these quickstarts, it is highly recommended you follow the Quick Start instructions below rather that setup your own environment from scratch.

The quickstarts have the following requirements:
- Azure subscription. You will need a valid and active Azure account to complete the quickstarts. If you do not have one, you can sign up for a [free trial](https://azure.microsoft.com/en-us/free/).
- An environment, which can by any of the following:
    - [Azure Notebooks](https://notebooks.azure.com/)
    - [Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview)
    
The following sections describe the setup process for each environment.

# Azure Quotas Required
The quickstarts depend on the capability to utilize a certain quantity of Azure resources, for which your Azure subscription will need to have sufficient quota available. 

The following are the specific quotas required, if your subscription does not meet the quota requirements in the region in which you will perform the quickstarts, you will need to request a quota increase thru Azure support:

Compute-VM
- Quota: Standard NC Family vCPU
- Provider: Microsoft.Compute
- SKU family: NC Promo Series
- Required Limit: 24

Compute-VM
- Quota: Total Regional vCPUs
- Provider: Microsoft.Compute
- SKU family: Dv2 Series
- Required Limit: 8

# Quickstart: Azure Notebooks

1. Please follow the steps outlined in [Azure Notebooks Setup](./azure-notebooks-setup) before continuing. 

2. Once the setup is done, you can then follow the steps as outlined for each of other quickstarts.


# Quickstart: Azure Notebook VMs

1. Please follow the steps outlined in [Azure Notebook VM Setup](./azure-notebook-vm-setup) before continuing. 

2. Once the setup is done, you can then follow the steps as outlined for each of other quickstarts.


# Quickstart: Visual Studio Code

1. Install [Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview) on your machine.

2. Install the latest version of [Anaconda](https://www.anaconda.com/distribution/).

3. Setup a new conda environment for Azure Auto ML. The easiest way to do that is to download the automl_setup script for your machine (Windows-automl_setup.cmd, Linux-automl_setup_linux.sh, Mac-automl_setup_mac.sh) and the common automl_env.yml file from the following [GitHub repository](https://github.com/Azure/MachineLearningNotebooks/tree/master/how-to-use-azureml/automated-machine-learning). Open command prompt or terminal and go to the directory where the two files are saved and run the script file. The script will creates a new conda environment called `azure_automl`, and installs the necessary packages.

4. From starter-artifacts navigate to the [visual-studio-code](../starter-artifacts/visual-studio-code) and download the project files to your local computer. Also remember to maintain the folder structure as shown in `starter-artifacts/visual-studio-code`, so that each quickstart’s starting python file is in its own folder. During the quickstarts , other files will be either downloaded or created, thus maintaining the folder structure will help keeping the files within their respective quickstart folders. 

5. When you are ready to start a quickstart: (1) start Visual Stuido Code, (2) go to File->Open Menu, and (3) open the **folder** for the quick start. For example, to work on `quickstart-1.1`, open the folder `01-aml-pipelines` from Visual Studio Code. This will ensure that the current working directory for the quickstart’s starting python file will set correctly.  
6. In VS code, when you first open the starting python file for a quickstart, use Select Interpreter command from the Command Palette (⇧⌘P) and select the azure_automl as your interpreter.

## Open the starting Python file

1. On your local computer expand the folder `00-aml-setup`.
2. Open Visual Studio Code by double clicking the starting python file: `00-aml-setup.py`.
3. Confirm that you have setup azure_automl as your interpreter.
4. To execute each step click on Run Cell just above the block of code.
5. Follow the instructions within the python file to complete the quickstart.
