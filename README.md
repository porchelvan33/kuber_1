# KIAQ Kubernetes Fundamentals Lab Assessment

## Project Overview

This project demonstrates basic Kubernetes concepts using Minikube, kubectl and Nginx.

## Tasks Completed

1. Installed Minikube and kubectl
2. Created Kubernetes namespace
3. Created Nginx Deployment
4. Exposed Nginx using NodePort Service
5. Created ConfigMap and Secret
6. Created PersistentVolume and PersistentVolumeClaim
7. Mounted persistent storage into Nginx
8. Scaled the deployment replicas
9. Performed rolling update
10. Performed rollback
11. Verified Pods, Services and Deployments

## Kubernetes Resources

- Namespace: k8s-lab
- Deployment: nginx-deployment
- Service: nginx-service
- ConfigMap: app-config
- Secret: app-secret
- PersistentVolume: nginx-pv
- PersistentVolumeClaim: nginx-pvc

## Verification Commands

```bash
kubectl get pods
kubectl get svc
kubectl get deployments
kubectl get pv
kubectl get pvc
kubectl get configmap
kubectl get secrets
