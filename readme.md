# Kubernetes Deployment of Dockerized Web App

> ⚠️ **Disclaimer:** This project is for learning purposes to practice deploying Dockerized applications with Kubernetes.

## Overview

This project demonstrates deploying a **multi-container web application** on Kubernetes:

- **Frontend:** React served via Nginx  
- **Backend:** Node.js / Express API  
- **Database:** MongoDB StatefulSet with PVC  

The goal is **to learn Kubernetes concepts**, such as:

- Deployments and Services  
- StatefulSets for databases  
- Persistent Volumes (PVC)  
- Cluster networking and port-forwarding  