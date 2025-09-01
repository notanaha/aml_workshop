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

Clone this repository on Azure ML Terminal.
Use the azureml_py310_sdkv2 kernel to run the notebooks below.

- 01_train.ipynb
- 02_endpoint.ipynb
- 03_pipeline.ipynb

You may need to pip install python-dotenv manually.
