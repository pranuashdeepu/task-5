# 🚀 Kubernetes Cluster with Minikube - Task 5 (DevOps Internship)

## 📌 Objective
Deploy and manage applications in a **local Kubernetes cluster** using Minikube, `kubectl`, and Docker.

---

## 🛠 Tools Used
- **Minikube** – Local Kubernetes cluster setup
- **Kubectl** – Kubernetes CLI tool
- **Docker** – Container runtime for images

---

## 📂 Project Files
- `deployment.yaml` – Deployment configuration for the application
- `service.yaml` – Service configuration to expose the app
- `screenshots/` – Screenshots of pods, services, scaling, and logs

---

## 📝 Steps Performed

### 1. Installed Required Tools
- Installed **Docker**, **Kubectl**, and **Minikube**.

### 2. Started Minikube Cluster
```bash
minikube start --driver=docker
