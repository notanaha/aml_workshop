# Azure ML Workshop

This repository provides a concise end-to-end workshop on Azure ML Workspace.

## Structure

- 01_train.ipynb – Train a model
- 02_endpoint.ipynb – Create and test an endpoint
- 03_pipeline.ipynb – Orchestrate a simple pipeline
- diabetes_data.csv – Training data
- diabetes_query.csv – Sample input rows for scoring
- scripts/
  - train-diabetes.py – Train model
  - evaluate.py – Evaluate metrics
  - register.py – Register the model
  - score-diabetes.py – Sample scoring
- component/ – Component YAMLs (train/evaluate/register)
- environments/ – Environment YAML (diabetes-env-01.yml)

## Quickstart

Clone this repository from the Azure ML terminal.
Use the **azureml_py310_sdkv2** kernel to run the notebooks.
<br>When using **azureml_py310_sdkv2**, you don’t need to install the packages from requirements.txt, but you may need to install python-dotenv manually.

Run notebooks.
- 01_train.ipynb
- 02_endpoint.ipynb
- 03_pipeline.ipynb


