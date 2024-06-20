Azure ML Workspace


# Introduction

\


Introductory or background materials:

- [What is Azure Machine Learning?](https://learn.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning?view=azureml-api-2\&WT.mc_id=APC-MachineLearning)

- [Azure Machine Learning documentation](https://learn.microsoft.com/en-us/azure/machine-learning/?view=azureml-api-2\&WT.mc_id=APC-MachineLearning)

- Training: [Explore Azure Machine Learning workspace resources and assets](https://learn.microsoft.com/en-us/training/modules/explore-azure-machine-learning-workspace-resources-assets/)

- [Manage Azure resource groups by using the Azure portal](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal) (ML Workspaces are created within a resource group)

- [Enable preview features for Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-enable-preview-features?view=azureml-api-2)


# Workspace Basics

## Creating an Azure ML Workspace

[Tutorial: Create resources you need to get started](https://learn.microsoft.com/en-us/azure/machine-learning/quickstart-create-resources?view=azureml-api-2)


### Quotas

- [Manage and increase quotas and limits for resources with Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-quotas?view=azureml-api-2)


## Compute Endpoints/Targets

Also see the [Azure Development VM](https://docs.google.com/document/d/1Na2eGx_V4kZfkrbJCkJ5lG9Ul5J_iNUJ8fffUJ0DD7Y/edit?usp=sharing) doc for more info about Azure GPU VMs

- [What are compute targets in Azure Machine Learning?](https://learn.microsoft.com/en-us/azure/machine-learning/concept-compute-target?view=azureml-api-2)

- [Create an Azure Machine Learning compute instance](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-compute-instance?view=azureml-api-2\&tabs=python)

- [Manage an Azure Machine Learning compute instance](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-compute-instance?view=azureml-api-2\&tabs=python)

- [Endpoints for inference in production](https://learn.microsoft.com/en-us/azure/machine-learning/concept-endpoints?view=azureml-api-2)


### Serverless

- [Online endpoints and deployments for real-time inference](https://learn.microsoft.com/en-us/azure/machine-learning/concept-endpoints-online?view=azureml-api-2#managed-online-endpoints-vs-kubernetes-online-endpoints)

- [Deploy and score a machine learning model by using an online endpoint](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-online-endpoints?view=azureml-api-2\&tabs=cli)

- [Model training on serverless compute](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-serverless-compute?view=azureml-api-2\&tabs=python)

- [Deploy a model as an online endpoint](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-deploy-model?view=azureml-api-2)


### Clusters

- [Create an Azure Machine Learning compute cluster](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-attach-compute-cluster?view=azureml-api-2\&tabs=python)

-


## Azure ML Studio (Portal)

<https://portal.azure.com/#home>


### Notebooks and Files

- [How to create and manage files in your workspace](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-files?view=azureml-api-2)

- [How to create an SMB Azure file share](https://learn.microsoft.com/en-us/azure/storage/files/storage-how-to-create-file-share?tabs=azure-portal#advanced)


### Users

- [Assign Azure roles to external users using the Azure portal](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-external-users)

- [Managed identities in Azure Container Apps](https://learn.microsoft.com/en-us/azure/container-apps/managed-identity?tabs=portal%2Cdotnet)


## Interacting with Resources

Also see the [Python SDK](https://docs.google.com/document/d/16Yr9tvgfH-rWVzNTGxNPCAC3dr7fUsUPF_YVL3cF44Q/edit#heading=h.hmk2us1kgf4r) section below

- [Access a compute instance terminal in your workspace](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-access-terminal?view=azureml-api-2)

- [Manage compute resources for model training and deployment in studio](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-attach-compute-studio?view=azureml-api-2)

- [Manage Azure Machine Learning workspaces in the portal or with the Python SDK (v2)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace?view=azureml-api-2\&tabs=python) 

- [Manage Azure Machine Learning registries](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-registries?view=azureml-api-2\&tabs=cli)


### Azure CLI

- [Install and set up the CLI (v2)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-configure-cli?view=azureml-api-2\&tabs=public)

- [Manage Azure Machine Learning workspaces using Azure CLI](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-workspace-cli?view=azureml-api-2\&tabs=createnewresources)

- More about Azure CLI vs. Python SDK: 

  - [What is Azure Machine Learning CLI and Python SDK v2?](https://learn.microsoft.com/en-us/azure/machine-learning/concept-v2?view=azureml-api-2)


## MLflow

- [MLflow and Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/concept-mlflow?view=azureml-api-2)

- [Configure MLflow for Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-mlflow-configure-tracking?view=azureml-api-2\&tabs=cli%2Cmlflow)

- [Guidelines for deploying MLflow models](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-deploy-mlflow-models?view=azureml-api-2\&tabs=azureml)

- [Log metrics, parameters, and files with MLflow](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-log-view-metrics?view=azureml-api-2\&tabs=interactive)

- Training: [Track model training in Jupyter notebooks with MLflow](https://learn.microsoft.com/en-us/training/modules/track-model-training-jupyter-notebooks-mlflow/?WT.mc_id=APC-MachineLearning)


## Key Vault

- [About Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview)

- [Azure Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/)


## Azure Container Registry

- [Azure Container Registry documentation](https://learn.microsoft.com/en-us/azure/container-registry/)

- [Introduction to Azure Container Registry](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-intro)

- Docker doc on [Azure Container Registry integration](https://docs.docker.com/scout/integrations/registry/acr/)


## Environments

- [What are Azure Machine Learning environments?](https://learn.microsoft.com/en-us/azure/machine-learning/concept-environments?view=azureml-api-2)

- [Manage Azure ML environments with CLI & SDK](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-manage-environments-v2?view=azureml-api-2\&tabs=cli#use-a-curated-environment)


## Data

### Overview

- Training: [Make data available in Azure Machine Learning](https://learn.microsoft.com/en-us/training/modules/make-data-available-azure-machine-learning/?WT.mc_id=APC-MachineLearning)

- [Tutorial: Upload, access and explore your data in Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-explore-data?view=azureml-api-2)


### Storage

- [Create an Azure storage account](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal)

- [Storage account overview](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview)

- [Create datastores](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-datastore?view=azureml-api-2\&tabs=sdk-identity-based-access%2Csdk-adls-identity-access%2Csdk-azfiles-accountkey%2Csdk-adlsgen1-identity-access%2Csdk-onelake-identity-access)

- [Choose a big data storage technology in Azure](https://learn.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/data-storage)

- [Import data assets (preview)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-import-data-assets?view=azureml-api-2\&tabs=cli#import-data-assets-preview)

- [Network routing preference for Azure Storage](https://learn.microsoft.com/en-us/azure/storage/common/network-routing-preference)


### Data Endpoints

- [Create connections (preview)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-connection?view=azureml-api-2\&tabs=cli)


# Azure ML Python SDK

## Introduction & Docs

- [What is the Azure Machine Learning SDK for Python?](https://learn.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py)

- [Azure ML Package client library for Python - version 1.15.0](https://learn.microsoft.com/en-us/python/api/overview/azure/ai-ml-readme?view=azure-python)


## Manage Resources

- [MLClient Class](https://learn.microsoft.com/en-us/python/api/azure-ai-ml/azure.ai.ml.mlclient?view=azure-python#methods)

- [Workspace Class](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.workspace.workspace?view=azure-ml-py#azureml-core-workspace-workspace-from-config)

- [core Package](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core?view=azure-ml-py)

- [compute Package](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute?view=azure-ml-py)

- [ComputeTarget Class](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute.computetarget?view=azure-ml-py)

- [amlcompute Module](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute.amlcompute?view=azure-ml-py)


### Remote Compute Targets

- [RemoteCompute Class](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute.remote.remotecompute?view=azure-ml-py)

- [remote Module](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute.remote?view=azure-ml-py)

- [RemoteComputeAttachConfiguration Class](https://learn.microsoft.com/en-us/python/api/azureml-core/azureml.core.compute.remote.remotecomputeattachconfiguration?view=azure-ml-py#azureml-core-compute-remote-remotecomputeattachconfiguration-validate-configuration)


# Running Training Jobs & Pipelines

Also see the [Serverless](https://docs.google.com/document/d/16Yr9tvgfH-rWVzNTGxNPCAC3dr7fUsUPF_YVL3cF44Q/edit#heading=h.8hck1wwdgjro) section above


## Jobs

- [Configure and submit training jobs](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-set-up-training-targets?view=azureml-api-1\&viewFallbackFrom=azureml-api-2#select-a-compute-target)

- [Tutorial: Train a model in Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-train-model?view=azureml-api-2)

- [Train models with Azure Machine Learning CLI, SDK, and REST API](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-train-model?view=azureml-api-2\&tabs=python)


## ML Pipelines

- [What are Azure Machine Learning pipelines?](https://learn.microsoft.com/en-us/azure/machine-learning/concept-ml-pipelines?view=azureml-api-2)

- [Create and run machine learning pipelines using components with the Azure Machine Learning CLI](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-component-pipelines-cli?view=azureml-api-2)

- [Tutorial: Create production machine learning pipelines](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-pipeline-python-sdk?view=azureml-api-2)

- [How to use pipeline component to build nested pipeline job (V2)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-pipeline-component?view=azureml-api-2)


# Monitoring / Inference

- [Visualize training results in studio (preview)](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-visualize-jobs?view=azureml-api-2)

- [Collect production data from models deployed for real-time inferencing](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-collect-production-data?view=azureml-api-2\&tabs=azure-cli) with Azure CLI (or [python SDK](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-collect-production-data?view=azureml-api-2\&tabs=python))

- [Application Insights overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)


# Automation

## MLOps

- [MLOps: Model management, deployment, and monitoring with Azure Machine Learning](https://learn.microsoft.com/en-us/azure/machine-learning/concept-model-management-and-deployment?view=azureml-api-2)

- [Set up MLOps with GitHub](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-setup-mlops-github-azure-ml?view=azureml-api-2\&tabs=azure-shell#deploying-the-model-training-pipeline)


## AutoML

- [What is automated machine learning (AutoML)?](https://learn.microsoft.com/en-us/azure/machine-learning/concept-automated-ml?view=azureml-api-2)

- [Tutorial: Train an object detection model with AutoML and Python](https://learn.microsoft.com/en-us/azure/machine-learning/tutorial-auto-train-image-models?view=azureml-api-2\&tabs=cli)


# Other Relevant Documentation Links

## Azure ML

- [What is infrastructure as code (IaC)?](https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code)

- .


## GitHub

- [Secret Scanning Patterns](https://docs.github.com/en/code-security/secret-scanning/secret-scanning-patterns)

  - [Supported Secrets](https://docs.github.com/en/code-security/secret-scanning/secret-scanning-patterns#supported-secrets)

- [Protected Branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches)

  - [Lock branch](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#lock-branch)

  - [Require status checks before merging](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#require-status-checks-before-merging)

- [Connecting to GitHub with SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

  - Edit your keys on your profile: <https://github.com/settings/keys>

  - GitHub doc on [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

  - Azure doc on [SSH key pairs for Linux VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys)


# Repo Links

## Our Repos

- [NOAA-PSL/ml-infrastructure](https://github.com/NOAA-PSL/ml-infrastructure)

- [NOAA-PSL/graph-ufs](https://github.com/NOAA-PSL/graph-ufs)

  - [P0 Release](https://github.com/NOAA-PSL/graph-ufs/releases/tag/p0)

  - [P0 Training PR](https://github.com/NOAA-PSL/graph-ufs/pull/6)

  - [Fix multi-threading PR](https://github.com/NOAA-PSL/graph-ufs/pull/65)


## Other Repos

### Google

- [google-deepmind/graphcast](https://github.com/google-deepmind/graphcast)

  - Issue: [Inference on multiple TPU cores / GPUs](https://github.com/google-deepmind/graphcast/issues/33)


### Azure/Microsoft

- [Azure/MachineLearningNotebooks](https://github.com/Azure/MachineLearningNotebooks)

  - [Train on remote VM (notebook)](https://github.com/Azure/MachineLearningNotebooks/tree/master/how-to-use-azureml/training/train-on-remote-vm)

  - [Train on local (notebook)](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/training/train-on-local/train-on-local.ipynb)

  - [Using Environments (notebook)](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/training/using-environments/using-environments.ipynb)

- [Microsoft/MLOpsPython](https://github.com/Microsoft/MLOpsPython)

- [microsoft/MLOps](https://github.com/microsoft/MLOps)

- [Azure/az-hop](https://github.com/Azure/az-hop) (Azure HPC On-Demand Platform provides an HPC Cluster Ready solution)


### Potentially Interesting

- [ai-models For All](https://github.com/darothen/ai-models-for-all)

