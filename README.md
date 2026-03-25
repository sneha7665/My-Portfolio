# DevOps Portfolio Deployment (Docker + Nginx)

## 📌 Project Overview
This project demonstrates containerization and deployment of a static portfolio website using Docker and Nginx, simulating a real-world cloud deployment workflow.

## 🚀 Tech Stack
- Docker
- Nginx
- HTML/CSS
- GitHub

## ⚙️ What I Implemented
- Containerized web application using Docker
- Configured Nginx as production web server
- Exposed application ports for external access
- Built reusable Docker image
- Ran containerized deployment locally

## 🏗 Architecture
User Browser → Docker Container → Nginx Server → Portfolio Website

## ☁️ Cloud Deployment Architecture (AWS Ready)

This application is designed following cloud deployment practices:

User → Internet → AWS EC2 Instance → Docker Container → Nginx → Portfolio Website

### Planned AWS Setup
- EC2 instance for compute
- Docker for containerization
- Nginx for web serving
- Security Groups for traffic control
- Public IP access via browser

This setup simulates a production-ready DevOps deployment.

## ▶️ How to Run

```bash
docker build -t devops-portfolio .
docker run -p 8080:80 devops-portfolio