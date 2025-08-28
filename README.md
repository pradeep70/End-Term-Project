# End-Term-Project
Building a Robust MLOps Pipeline

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/pradeep70/End-Term-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
python -m venv .venv
```

```bash
.venv\Scripts\activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```






## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/pradeep70/End-Term-Project.mlflow 


Run this to export as env variables:

```bash

import dagshub
dagshub.init(repo_owner='pradeep70', repo_name='End-Term-Project', mlflow=True)
python script.py

```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)