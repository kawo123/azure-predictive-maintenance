# Train RUL model for turbofan data using AutoML and Azure Notebooks

## Prerequisites

1. Before using these notebooks to train and deploy a classifier you need to have:

   - [Azure Machine Learning Compute Instance](https://docs.microsoft.com/en-us/azure/machine-learning/concept-compute-instance) as your development machine

   - Azure subscription ID

   - Azure resource group name

## Introduction

This project contains two Jupyter notebooks. The first notebook, [01-turbofan_regression_predictive_maintenance_train](./01-turbofan_regression_predictive_maintenance_train.ipynb) walks through the process of using the data from the turbofan devices to train a Remaining Useful Life (RUL) prediction model. The second notebook, [02-turbofan_regression_predictive_maintenance_deploy](./02-turbofan_regression_predictive_maintenance_deploy.ipynb), depends on completion of the first and demonstrates how to create a deployable Edge module from the model created in the first notebook.

Throughout, we rely heavily on Jupyter notebooks for our explanation and execution of Machine Learning. If you have not used Jupyter and/or Azure Notebooks here are a couple of introductions to get you started.

1. Quickstart:  [Create and share a notebook](https://docs.microsoft.com/en-us/azure/notebooks/quickstart-create-share-jupyter-notebook)

1. Tutorial: [Create and run a Jupyter notebook with Python](https://docs.microsoft.com/en-us/azure/notebooks/tutorial-create-run-jupyter-notebook)
