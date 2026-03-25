# 🚀 DevOps Portfolio Deployment (Docker + Nginx)

## 📌 Project Overview
This project demonstrates containerization and deployment of a static portfolio website using Docker and Nginx.  
The goal is to simulate a real-world DevOps workflow where an application is packaged into a container and served through a production-grade web server, following cloud deployment practices.

---

## 🧰 Tech Stack
- Docker (Containerization)
- Nginx (Web Server)
- HTML / CSS (Frontend)
- Git & GitHub (Version Control)
- Cloud Architecture (AWS-ready design)

---

## 🚀 Skills Demonstrated
- Application containerization using Docker
- Production web serving with Nginx
- Image building and container lifecycle management
- Port mapping and service exposure
- Git workflow and version control
- Cloud deployment architecture planning

---

## ⚙️ Implementation Details
- Built a reusable Docker image for a static website
- Configured Nginx inside container for web hosting
- Exposed container ports for browser access
- Created deployment-ready project structure
- Documented DevOps workflow and architecture

---

## 🏗 Architecture Diagram

![Architecture](images/architecture.png)

### Flow
User Browser → Internet → AWS EC2 → Docker Container → Nginx → Portfolio Website

---

## ☁️ Cloud Deployment Architecture (AWS Ready)

This project is designed to be deployed on AWS using industry-standard practices.

### Planned AWS Setup
- **EC2 Instance** — Application hosting
- **Docker** — Containerized deployment
- **Nginx** — Reverse proxy & web server
- **Security Groups** — Traffic control
- **Public IP** — External access

This setup mirrors a production-ready DevOps deployment pipeline.

---

## ▶️ How to Run Locally

### 1️⃣ Build Docker Image
docker build -t devops-portfolio .

### 2️⃣ Run Container
docker run -p 8080:80 devops-portfolio

### 3️⃣ Open in Browser
http://localhost:8080