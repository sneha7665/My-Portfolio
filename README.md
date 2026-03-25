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

## ▶️ How to Run

```bash
docker build -t devops-portfolio .
docker run -p 8080:80 devops-portfolio