# 🚀 2-Tier Flask Application | DevOps Project

## 🌐 Live Demo

Application URL:

http://13.60.190.11:5000/

---

A containerized 2-Tier Application built using Flask and MySQL, demonstrating modern DevOps practices including Dockerization, container orchestration, infrastructure deployment, and application management on Linux servers.

## 📌 Project Overview

This project follows a **2-Tier Architecture** where:

* **Tier 1:** Flask Web Application
* **Tier 2:** MySQL Database

The application is fully containerized using Docker and deployed on a Linux server, showcasing practical DevOps skills such as container management, networking, deployment automation, and troubleshooting.

---

## 🏗️ Architecture

```text
                    ┌─────────────────┐
                    │     Users       │
                    └────────┬────────┘
                             │
                             ▼
                    ┌─────────────────┐
                    │  Flask App      │
                    │ Docker Container│
                    └────────┬────────┘
                             │
                    Docker Network
                             │
                             ▼
                    ┌─────────────────┐
                    │   MySQL DB      │
                    │ Docker Container│
                    └─────────────────┘
```

---

## 🛠️ Tech Stack

### Application Layer

* Python
* Flask

### Database Layer

* MySQL

### DevOps Tools

* Docker
* Docker Compose
* Git
* GitHub

### Platform

* Linux (Ubuntu)
* AWS EC2

---

## 🔥 DevOps Practices Implemented

✅ Containerization using Docker

✅ Multi-container deployment using Docker Compose

✅ Service-to-Service Communication

✅ Docker Networking

✅ Infrastructure Deployment on AWS EC2

✅ Linux Server Administration

✅ Version Control using Git & GitHub

✅ Container Monitoring and Troubleshooting

✅ Persistent Database Storage

---

## 📂 Project Structure

```text
2-tier-flask-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
├── templates/
├── static/
└── README.md
```

---

## 🐳 Docker Implementation

### Build Images

```bash
docker-compose build
```

### Start Containers

```bash
docker-compose up -d
```

### Verify Running Containers

```bash
docker ps
```

### View Logs

```bash
docker-compose logs -f
```

### Stop Services

```bash
docker-compose down
```

---

## ☁️ AWS Deployment

The application was deployed on an AWS EC2 Ubuntu instance.

### Deployment Workflow

1. Launch EC2 Instance
2. Configure Security Groups
3. Install Docker & Docker Compose
4. Clone GitHub Repository
5. Build Docker Images
6. Start Containers
7. Access Application via Public IP

---

## 📈 Key Learning Outcomes

* Containerized Application Deployment
* Docker Networking Concepts
* Linux Administration
* AWS EC2 Management
* Troubleshooting Container Issues
* Infrastructure Setup and Management
* Version Control Workflows
* Application Deployment Lifecycle

---

## 🔮 Future Enhancements

* CI/CD Pipeline using Jenkins
* GitHub Actions Integration
* Kubernetes Deployment
* Monitoring with Prometheus & Grafana
* Nginx Reverse Proxy
* Infrastructure as Code using Terraform

---
