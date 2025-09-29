# HPA-in-Kubernetes
This project is part of my DevOps portfolio, showcasing Kubernetes scaling features using HPA.

# 🚀 Kubernetes Horizontal Pod Autoscaler (HPA)

This project demonstrates how to use a **Horizontal Pod Autoscaler (HPA)** in Kubernetes to scale workloads based on **CPU and Memory utilization**.

---

## 📌 Why HPA?
Kubernetes HPA automatically adjusts the number of pod replicas in a deployment to match real-time demand.  
- Keeps applications **responsive** under heavy load.  
- Saves **costs** by reducing replicas during idle time.  
- Ensures **stability and availability** in production environments.  

---

## 🔧 What’s Inside
- **Namespace** → Isolates the workload.  
- **Deployment** → A CPU/Memory intensive Python container simulating load.  
- **HPA** → Scales the deployment between 1 and 10 replicas, based on both CPU and memory usage.

---

## 📂 Repository Structure
