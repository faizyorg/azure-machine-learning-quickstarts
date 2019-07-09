# Azure Machine Learning Service Quickstarts

[Azure Machine Learning Service](https://docs.microsoft.com/en-us/azure/machine-learning/service/overview-what-is-azure-ml) is a cloud service for machine learning that support training, deploying, managing, and operationalizing (MLOps) models in Azure using Python SDK and CLI. Azure Machine Learning service also provides a visual interface (preview) to quickly, prepare data, and train machine learning models.


## 1. Azure Machine Learning Python SDK

The following set of quickstarts demonstrate a key set of Azure Machine Learning Services and provides instructions for you to perform them using a Python environment in Visual Studio Code.

### 1.0 Setting up your environment

This provides the instructions to get started with the lab.

### 1.1 Azure Machine Learning Pipelines

The goal of this quickstart is to build machine learning pipelines using Azure Machine Learning Python SDK that demonstrate the basic data science workflow of data preparation, model training, and predictions.

### 1.2 MLOps with Azure Machine Learning Service and Azure DevOps

The goal of this quickstart is to build a simple use case that shows how you can operationalize your machine learning models that leverages the Azure DevOps Machine Learning extension, CLI extension for Azure Machine Learning service, and Azure Machine Learning Pipelines that integrate with Azure DevOps CI/CD and deployment workflows.

### 1.3 Automated Machine Learning

This quickstart consists of two parts. In the first part, you learn how to create, run, and explore automated machine learning experiments in the Azure portal without a single line of code. In the second part, you will use compute resources provided by Azure Machine Learning service to remotely train a set of models using Automated Machine Learning using Azure ML Python SDK.

### 1.4 Deep Learning with Azure Machine Learning

In this quickstart, you will train a deep learning model to classify the descriptions of car components as compliant or non-compliant. You will train the model on Azure Machine Learning Compute Cluster, download the trained model to your local computer, and make predictions.

### 1.5 Creating ONNX models with Azure Machine Learning

In this quickstart, your will convert a Deep Learning model you trained in **quickstart-1.4** to ONNX format and deploy the ONNX model as a web service to make inferences. You will also measure the speed of the ONNX runtime for making inferences and compare the speed of ONNX with Keras for making inferences.

### 1.6 Model Interpretability with Azure Machine Learning

The goal of this quickstart is to show Model interpretability with Azure Machine Learning service. You will learn how to explain why your model made the prediction it made by using the Azure Machine Learning Interpretability SDK. You will learn to understand both global and local explainability of your model. Finally, you will also learn how to deploy the explainer along with the model to be used at scoring time to make predictions and provide local explanations.

### 1.7 Deployment of Automated Machine Learning Model

In this quickstart, you will start with a model that was trained using Automated Machine Learning. Learn how to use the Azure ML Python SDK to register, package, and deploy the trained model to Azure Container Instance as a scoring web service. Finally, test the deployed model (1) by make direct calls on service object, (2) by calling the service end point (Scoring URI) over http.

