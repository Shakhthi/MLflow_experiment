## ML FLow experiements

MLFLOW_TRACKING_URI=https://dagshub.com/Shakhthi/MLflow_experiment.mlflow \
MLFLOW_TRACKING_USERNAME=Shakhthi \
MLFLOW_TRACKING_PASSWORD=ccde511fd6c71ff975c0a5ab28a4d5d71d33c598 \
python script.py

import dagshub
dagshub.init(repo_owner='Shakhthi', repo_name='MLflow_experiment', mlflow=True)

