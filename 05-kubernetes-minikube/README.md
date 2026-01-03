
# 05 - Kubernetes (Minikube)

## What this shows
Deployment of a containerized application on a local Kubernetes cluster using declarative manifests.

## Tech stack
- Kubernetes
- Minikube
- kubectl
- Docker

## Architecture
- Deployment (2 replicas)
- Service (NodePort)
- Local Kubernetes cluster

## How to run
minikube start
kubectl apply -f manifests/
minikube service nginx-service
git add .
git commit -m 
git push

## Screenshots
Nginx welcome page - Open from minikube service nginx-service