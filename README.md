# MLOPs-Production-Ready-Machine-Learning-Project
Anaconda: https://www.anaconda.com/
Vs code: https://code.visualstudio.com/download
Git: https://git-scm.com/
Flowchart: https://whimsical.com/
MLOPs Tool: https://www.evidentlyai.com/
MongoDB: https://account.mongodb.com/account/login
Data link: https://www.kaggle.com/datasets/moro23/easyvisa-dataset

# Git commands
git add .

git commit -m "Updated"

git push origin main

# How to run?

conda create -n visa python=3.10 -y

conda activate visa

pip install -r requirements.txt

if there is any issue in mongod connectivity [timeout error or data ingestion from mongodb] then 

pip install --upgrade pymongo dnspython

# Workflow:

- constants
- entity
- components
- pipeline
- Main file

# Export the environment variable

export MONGODB_URL="mongodb+srv://<username>:<password>...."

export AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID>

export AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY>

pip install --upgrade numexpr

After executing app.py enter following to give input independent variables for prediction

http://localhost:8080