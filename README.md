# 🧩 Kubernetes Manifests

A collection of Kubernetes YAML configuration files for **Deployments**, **ReplicaSets**, **StatefulSets**, and **DaemonSets**.  
This repository demonstrates key Kubernetes concepts and is part of my DevOps learning journey — focused on container orchestration, scalability, and automation.

---

## 📁 Repository Structure

kubernetes-manifests/
├── deployment/
│ └── nginx-deployment.yml
├── replicaset/
│ └── nginx-replicaset.yml
├── statefulset/
│ └── mysql-statefulset.yml
├── daemonset/
│ └── monitoring-daemonset.yml
└── README.md

yaml
Copy code

---

## 🚀 Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/kubernetes-manifests.git
cd kubernetes-manifests
```
### 2. Apply the manifests

Make sure you have a running Kubernetes cluster (like Kind, Minikube, or Docker Desktop).

kubectl apply -f deployment/nginx-deployment.yml
kubectl apply -f replicaset/nginx-replicaset.yml
kubectl apply -f statefulset/mysql-statefulset.yml
kubectl apply -f daemonset/monitoring-daemonset.yml

### 3. Verify resources
kubectl get all -n <namespace>

🧠 Concepts Covered

✅ Deployments — Manage stateless applications

✅ ReplicaSets — Ensure pod replicas and high availability

✅ StatefulSets — Manage stateful applications with persistent storage

✅ DaemonSets — Run background agents on all nodes

✅ Namespaces — Logical isolation and resource grouping

🛠️ Tools Used

Kubernetes (v1.29+)

kubectl CLI

Kind / Minikube (for local clusters)

Docker

📘 Learning Goals

Practice writing and applying Kubernetes manifests

Understand workload controllers and their use cases

Gain hands-on experience with YAML configuration and cluster management

👨‍💻 Author
Mohammed Khaleel
