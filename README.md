# Chest-Disease-Classification-from-chest-CT-Scan-Image

## Workflows:==>

1]Update config.yaml

2]Update params.yaml

3]Update the entity

4]Update the configuration manager in src config

5]Update the components

6]Update the pipeline

7]Update the main.py

8]Update the dvc.yaml

## mlflows:==>

#dogshub

import dagshub
dagshub.init(repo_owner='sunilkulkarni603', repo_name='ml_flow_exp_demo', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


===> 
MLFLOW_TRACKING_URI=https://dagshub.com/sunilkulkarni603/ml_flow_exp_demo.mlflow
MLFLOW_TRACKING_USERNAME=sunilkulkarni603
MLFLOW_TRACKING_PASSWORD=
python script.py