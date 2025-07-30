# 🚀 nginx-argo-app

This repository contains a basic Kubernetes deployment of the **NGINX web server** using **Kustomize**.  
It is designed for **GitOps-based delivery** via **Argo CD**.

---

## 📁 Files

- `deployment.yaml` – Defines an NGINX Deployment  
- `service.yaml` – Exposes the NGINX pod via ClusterIP  
- `kustomization.yaml` – Combines the deployment and service using Kustomize  

---

## ✅ Prerequisites

To deploy this application, ensure you have the following:

- A running **Kubernetes cluster** (e.g., Minikube, Kind, or any cloud-managed service)
- **Argo CD** installed and configured in the cluster
- `kubectl` and `kustomize` installed (for local testing, optional)

---

## 🚀 How to Deploy

You can deploy this app via **Argo CD** by pointing it to this repository:

1. Add this Git repo to Argo CD:
   ```bash
   argocd repo add https://github.com/ahmadu2305/nginx-argo-app.git
