![Deployment Status](https://github.com/Endeshaw90/DevOps_Resume/actions/workflows/pages-build-deployment/badge.svg)
# 🚀 DevOps Resume Container

A containerized professional resume demonstrating a complete **local-to-cloud** CI/CD pipeline using Docker and GitHub Actions.

## 🛠️ Tech Stack
* **Web Server:** Nginx (Alpine)
* **Containerization:** Docker
* **CI/CD:** GitHub Actions
* **Hosting:** GitHub Pages

## ⚡ Quick Start (Local)
Run this resume locally in seconds:
```bash
docker build -t devops-resume .
docker run -d -p 8080:80 --name resume-app devops-resume

## 🌐 Live Demo
Access the production deployment here:

👉 [**View My Live Resume**](https://endeshaw90.github.io/DevOps_Resume/)