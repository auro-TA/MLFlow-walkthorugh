# Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains the resources for basic tutorial on MLFlow.

# Basic setup

## Setup the environment 
  - create a new environment: `conda create -f conda.yaml`
  - activate the environment: `conda activate mlflow-env`

## The notebook
- Get the `hands_on_example.ipynb`
- run `pip install jupyter`
- run `jupyter notebook`

## To run the mlflow'
`pip install mlflow`
`mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 0.0.0.0 --port 5000 `

## Screenshot of ML flow UI
![ML Flow 1](https://github.com/auro-TA/MLFlow-walkthorugh/assets/149032327/b6eb2cf8-5f6a-4c88-b6d9-7653c8408fce)
