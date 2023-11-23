This is my first End To End Machine Learning Project

## STEPS


### first initialize the git
git init

git add abc.txt

git add .

git commit -m "this is my first commit"

git pull

bash your_file_name.sh

python setup.py install

### another way you can mention -e . in your requirement file and you can run

pip install -r requirements.txt

### MLflow
Documentation

local cmd
  * mlflow ui


### dagshub
dagshub

MLFLOW_TRACKING_URI=https://dagshub.com/Anna-Elsa-Luiz/End_to_End_ML_Project.mlflow 
MLFLOW_TRACKING_USERNAME=Anna-Elsa-Luiz 
MLFLOW_TRACKING_PASSWORD=61ea7cc63a547cee2bfa163992db880d6b571b70
python script.py

**Run this to export as env variables:**

export MLFLOW_TRACKING_URI=https://dagshub.com/Anna-Elsa-Luiz/End_to_End_ML_Project.mlflow

export MLFLOW_TRACKING_USERNAME=Anna-Elsa-Luiz

export MLFLOW_TRACKING_PASSWORD=61ea7cc63a547cee2bfa163992db880d6b571b70




DVC cmd
dvc init
dvc repro
dvc dag