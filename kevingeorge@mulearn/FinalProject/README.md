# 🚀 My First Scalable Web App

## 📌 Overview
This project demonstrates deploying a containerized web application using Docker and Kubernetes (KIND), showcasing scalability and self-healing capabilities.

## ⚙️ Tech Stack
- Docker
- Kubernetes (KIND)
- Nginx

## 🚀 Features
- Containerized web app using Docker
- Kubernetes deployment with 3 replicas
- Service exposure using NodePort
- Environment variable injection (STUDENT_NAME)
- Self-healing (auto pod recreation)

## 📂 Project Structure
FinalProject/
├── Dockerfile
├── deployment.yaml
├── service.yaml
├── index.html
├── screenshots/

## 🧪 Steps Performed
1. Built Docker image
2. Loaded image into KIND cluster
3. Deployed app with 3 replicas
4. Exposed service using NodePort
5. Verified scaling and self-healing

## 📸 Screenshots
- Pods running
- Service details
- Application in browser
- Self-healing demonstration

## 🧠 Key Learnings
- Kubernetes deployment & scaling
- Debugging image pull errors
- Service exposure in KIND
- Real-world DevOps workflow