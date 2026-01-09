# DevOps CI/CD Project

This project demonstrates a CI/CD pipeline using GitHub Actions to build a Dockerized application and deploy it to Kubernetes.

## Tech Stack
- Docker
- Kubernetes (Minikube)
- GitHub Actions
- Python (Flask)

## Workflow
1. Code pushed to GitHub
2. GitHub Actions builds Docker image
3. Application deployed to Kubernetes

## How to Run
- docker build -t devops-demo .
- kubectl apply -f kubernetes/
