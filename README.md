# datafun_07_ml

#### This file contains the documentation and commands related to the Module 7 Machine Learning Project

## Create Project
Created a new repo in GitHub with the name 'datafun-07-ml' 

Added the default README.md 

Named the script "bukola_ml.ipynb"

## Cloned project down to my machine
Opened VS Code 

Used file > open folder to access the folder where I want my project to reside

Opened a new terminal (with powershell as default) 

Used the 'git clone' command to clone the project to my machine

```shell

git clone site_URL

```

## Instructions for Setting up Virtual Environment
``` shell
python3 -m venv .venv
source .venv/bin/activate
```

## Installing dependencies and freezing requirements
```shell
python3 -m pip install jupyterlab pandas pyarrow matplotlib seaborn
python3 -m pip freeze > requirements.txt
```


## Git Commands
``` shell
git add .
git commit -m ""
git push origin main
