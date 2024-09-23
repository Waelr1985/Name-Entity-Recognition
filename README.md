# Name-Entity-Recognition

# Workflows

constants

config_entity

artifact_entity

components

pipeline

app.py



# Git commands

git add .

git commit -m "Updated"

git push origin master

# GCP Configuration

#Gcloud cli download link: https://cloud.google.com/sdk/docs/install#windows

gcloud init

# How to run?

conda create -n nerproj python=3.8 -y

conda activate nerproj

pip install -r requirements.txt

python app.py

# GCP CICD Deployment with CircleCI:

artifact registry --> create a repository

change line 42,50,72,76,54 in circleci config

Opne circleci --> create a project

Set Environment variables in CircleCI

GCLOUD_SERVICE_KEY --> service account

GOOGLE_COMPUTE_ZONE = asia-south1

GOOGLE_PROJECT_ID

Create a VM instances & setup scripts