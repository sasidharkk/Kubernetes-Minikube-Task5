# DevOps Internship – Task 5 
### Build a Kubernetes Cluster Locally with Minikube

This task involves deploying and managing an application on a local Kubernetes cluster using **Minikube**, **kubectl**, and **Docker**. The objective is to understand how deployments, services, and scaling work in Kubernetes.

---

### Tools Used
Minikube | kubectl | Docker Desktop | Git Bash

---

### Overview
A local Kubernetes cluster was created using **Minikube** with Docker as the driver. An **Nginx application** was deployed using a Deployment manifest and exposed through a Service. The application was then scaled to multiple replicas, verified through pods and services, and accessed via Minikube.

---

### 📄 Files Included
- `deployment.yaml` → Defines the Nginx deployment with 2 replicas.  
- `service.yaml` → Exposes the deployment as a NodePort service.  
- `README.md` → Documentation of the entire task.  
- `screenshots/` → Contains output proofs (`pods.png`, `services.png`, `app.png`).

---

### Key Learnings
- Setup and management of a Kubernetes cluster using Minikube.  
- Creation of Deployments and Services.  
- Scaling replicas and managing containers.  
- Accessing cluster applications locally.  
- Understanding NodePort, ClusterIP, and LoadBalancer concepts.
---


**Author:** Sasidhar Kondapaneni  
**Role:** DevOps Intern – Elevate Labs  
