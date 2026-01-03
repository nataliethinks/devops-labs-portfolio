
# 06 - Kubernetes Volumes (PVC)

## What this shows
Persistent storage in Kubernetes using PersistentVolumeClaims, decoupling application lifecycle from storage.

## Tech stack
- Kubernetes
- Minikube
- PersistentVolumeClaim
- Nginx

## Architecture
- Deployment with mounted PVC
- NodePort Service
- Local persistent volume via Minikube

## Key concepts demonstrated
- PVC lifecycle
- Pod vs storage separation
- Stateful workloads in Kubernetes

## Evidence
Screenshots demonstrate:
- PVC successfully bound
- Application reading data from persistent volume
- Data persistence after pod recreation