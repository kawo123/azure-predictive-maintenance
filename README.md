# Train RUL model for turbofan data using AutoML and Azure Notebooks

## Prerequisites

1. Before using these notebooks to train and deploy a classifier you need to have:

   - [Azure Machine Learning Compute Instance](https://docs.microsoft.com/en-us/azure/machine-learning/concept-compute-instance) as your development machine

## Introduction

This project contains two Jupyter notebooks inherited from the [Microsoft - Azure Samples - IoT Edge and ML Sample GitHub Repository](https://github.com/Azure-Samples/IoTEdgeAndMlSample). The first notebook, [01-turbofan_regression_predictive_maintenance_train](./01-turbofan_regression_predictive_maintenance_train.ipynb) walks through the process of using the data from the turbofan devices to train a Remaining Useful Life (RUL) prediction model. The second notebook, [02-turbofan_regression_predictive_maintenance_deploy](./02-turbofan_regression_predictive_maintenance_deploy.ipynb), depends on completion of the first and demonstrates how to create a deployable Edge module from the model created in the first notebook.

Throughout, we rely heavily on Jupyter notebooks for our explanation and execution of Machine Learning. If you have not used Jupyter and/or Azure Notebooks here are a couple of introductions to get you started.

1. Quickstart:  [Create and share a notebook](https://docs.microsoft.com/en-us/azure/notebooks/quickstart-create-share-jupyter-notebook)

1. Tutorial: [Create and run a Jupyter notebook with Python](https://docs.microsoft.com/en-us/azure/notebooks/tutorial-create-run-jupyter-notebook)

---

### PLEASE NOTE FOR THE ENTIRETY OF THIS REPOSITORY AND ALL ASSETS

1. No warranties or guarantees are made or implied.
2. All assets here are provided by me "as is". Use at your own risk. Validate before use.
3. I am not representing my employer with these assets, and my employer assumes no liability whatsoever, and will not provide support, for any use of these assets.
4. Use of the assets in this repo in your Azure environment may or will incur Azure usage and charges. You are completely responsible for monitoring and managing your Azure usage.

---

Unless otherwise noted, all assets here are authored by me. Feel free to examine, learn from, comment, and re-use (subject to the above) as needed and without intellectual property restrictions.

If anything here helps you, attribution and/or a quick note is much appreciated.
