# 1.0 Setting up your environment
# Azure Notebook VMs Setup

At a high level, here are the setup tasks you will need to perform to prepare your Azure Notebook VM Environment (the detailed instructions follow):

1. Import the Quickstart Notebooks

2. Update your Notebook Environment 



## Task 1: Import the Quickstart Notebooks

1. Log into [Azure Portal](https://portal.azure.com/) and open the pre-deployed machine learning workspace: quick-starts-ws-XXXXX.
2. Select **Notebook VMs**

3. Select the pre-created Notebook VM: **sandbox-XXXXX** and then select **Jupyter** open icon, to open Jupyter Notebooks interface.

   ![Open Jupyter Notebooks Interface](images/03.png)

4. Select **New, Terminal** as shown to open the terminal page.

   ![Open Terminal Page](images/04.png)
  
5. Run the following commands in order in the terminal window:

   a. `mkdir quick-starts`
   
   b. `cd quick-starts`
   
   c. `git clone https://github.com/solliancenet/azure-machine-learning-quickstarts.git`
   
      ![Clone Github Repository](images/05.png)
   
   d. Wait for the import to complete.


## Task 2: Update your Notebook Environment 

1.  From the Jupyter Notebooks interface, navigate to the `quick-starts->azure-machine-learning-quickstarts->aml-python-sdk->starter-artifacts->nbvm-notebooks` folder where you will find all your quickstart files.

   ![Find your QuickStart Notebooks](images/06.png)

2. Open notebook: **00-aml-setup/00-aml-setup.ipynb**

3. Run each cell in the notebook to install the required libraries.
