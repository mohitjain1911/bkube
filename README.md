# Kubernetes Application Project

## Overview
This project involves setting up and managing a Kubernetes cluster using Minikube. Docker containers for Django and React applications are deployed into Kubernetes pods, with a focus on achieving deployment replication, auto-healing, and auto-scaling.

## Key Components
1. **Kubernetes Cluster Setup**
   - Built using Minikube.

2. **Docker Container Management**
   - Managed Docker containers for Django and React applications.
   - Deployed containers into Kubernetes pods.

3. **Kubernetes Management**
   - Managed deployment replication.
   - Implemented auto-healing and auto-scaling for the Kubernetes cluster.
   - Managed network and services with host IP allocation.

## Setup Guide
1. **Install Prerequisites**
   - Minikube
   - Docker
   - kubectl
     
2. **Start Minikube**
```bash
minikube start
```

3. **Build and Deploy Docker Containers**

Build Docker images for your Django and React applications.
Create Kubernetes pods and services using kubectl apply -f <file-name>.yaml.

## Achievements
- Successfully reduced downtime in the production environment.

## Presentation
For a detailed presentation of the project, please refer to the uploaded project presentation (PPT).

## Conclusion
This project demonstrates the efficient setup and management of a Kubernetes cluster for deploying Django and React applications, ensuring minimal downtime and robust scaling capabilities.
