# nginx-argo-app

This repository contains a basic Kubernetes deployment of the NGINX web server using Kustomize.  
It is designed for GitOps-based delivery via Argo CD.

## 📁 Files
- `deployment.yaml`: Defines an NGINX Deployment
- `service.yaml`: Exposes NGINX via ClusterIP
- `kustomization.yaml`: Combines the deployment and service using Kustomize

## 🚀 How to Deploy
Use Argo CD to deploy this app by pointing it to this repository.

## 👤 Maintainer
Ahmed Samaila – [Yayyafi Global Resources](https://www.yayyafi.com/)
