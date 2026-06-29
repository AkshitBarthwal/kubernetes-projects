# Kubernetes Horizontal Pod Autoscaler (HPA) Project

## Project Overview

This project demonstrates how to automatically scale Kubernetes Pods using the Horizontal Pod Autoscaler (HPA) based on CPU utilization.

The application is deployed as a Kubernetes Deployment and exposed through a Service. The Metrics Server collects CPU metrics, and HPA automatically increases or decreases the number of Pods depending on CPU usage.

---

## Project Architecture

```
User
  │
  ▼
Kubernetes Service
  │
  ▼
Nginx Deployment
  │
  ▼
Metrics Server
  │
  ▼
Horizontal Pod Autoscaler
  │
  ▼
Pods Scale Automatically
```

---

## Technologies Used

* Ubuntu Linux
* Kind Kubernetes Cluster
* kubectl
* Kubernetes
* Metrics Server
* Horizontal Pod Autoscaler (HPA)
* YAML

---

## Features

* Kubernetes Deployment
* Kubernetes Service
* Metrics Server Integration
* CPU Resource Requests and Limits
* Horizontal Pod Autoscaler
* Automatic Pod Scaling
* Load Testing
* Auto Scale Up and Scale Down

---

## Project Files

* deployment.yaml
* service.yaml
* hpa.yaml

---

## How It Works

1. Deploy the Nginx application.
2. Expose it using a Kubernetes Service.
3. Install the Metrics Server.
4. Create the Horizontal Pod Autoscaler.
5. Generate CPU load.
6. Observe Pods scaling automatically.
7. Stop the load and watch the Pods scale back down.

---

## Learning Outcomes

* Kubernetes Deployments
* Services
* Resource Requests and Limits
* Metrics Server
* Horizontal Pod Autoscaler
* Kubernetes Monitoring
* Autoscaling Based on CPU Usage

---

## Screenshots

Screenshots of the deployment, metrics server, HPA, CPU usage, scaling process, and browser output are available in the screenshots folder.

---

## Author

Akshit Barthwal

