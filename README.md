# smart-manufacturing-mlops-platform


---

# `Smart-manufacturing-mlops-platform`

## Suggested Folder Structure
```text
smart-manufacturing-mlops-platform/
├── README.md
├── requirements.txt
├── Dockerfile
├── .gitignore
├── app/
│   ├── main.py
│   ├── model/
│   │   ├── train.py
│   │   ├── predict.py
│   │   └── evaluate.py
│   └── utils/
│       └── config.py
├── deploy/
│   ├── k8s/
│   │   ├── deployment.yaml
│   │   └── service.yaml
│   └── argocd/
│       └── application.yaml
├── jenkins/
│   └── Jenkinsfile
├── tests/
│   └── test_api.py
└── docs/
    └── architecture.png
```
# Smart Manufacturing MLOps Platform

A GitOps-based ML deployment platform for manufacturing use cases using ArgoCD, Jenkins, Docker, and Kubernetes.

## Overview
This project demonstrates how to deploy and manage machine learning services in a manufacturing-oriented environment using GitOps practices and automated CI/CD workflows.

## Features
- GitOps-based deployment with ArgoCD
- CI/CD automation with Jenkins
- Dockerized ML service
- Kubernetes deployment manifests
- Production-style release workflow
- Model service integration through API endpoints

## Tech Stack
- Python
- Docker
- Kubernetes
- ArgoCD
- Jenkins
- FastAPI or Flask

## Project Structure
- `app/` ML service and API
- `deploy/k8s/` Kubernetes manifests
- `deploy/argocd/` ArgoCD application config
- `jenkins/` CI/CD pipeline definition
- `tests/` deployment and API tests

## Run Locally
```bash
git clone https://github.com/hossain-sanowar/smart-manufacturing-mlops-platform
cd smart-manufacturing-mlops-platform
pip install -r requirements.txt
python app/main.py
```
## Deployment

This project uses:

Jenkins for build and CI
Docker for packaging
Kubernetes for deployment
ArgoCD for GitOps-based release management
Use Case

Built as a reference implementation for reliable ML deployment workflows in manufacturing-oriented systems.

## Author

Md Sanowar Hossain
