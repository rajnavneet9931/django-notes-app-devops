# 🚀 Django Notes App (DevOps Project)

## 📌 Overview
This is a production-ready Notes application built using **Django and React**, containerized with **Docker**, and deployed using a **3-tier architecture** with **Nginx, Gunicorn, and MySQL**.

---

## 🏗 Architecture

Client → Nginx → Gunicorn → Django → MySQL

---

## 🛠 Tech Stack

- Django (Backend)
- React (Frontend)
- Gunicorn (WSGI Server)
- Nginx (Reverse Proxy & Static Files)
- MySQL (Database)
- Docker & Docker Compose
- Jenkins (CI/CD)

---

## ⚙️ Features

- Multi-container Docker setup (nginx + django + mysql)
- Nginx reverse proxy configuration
- Gunicorn for production-ready Django serving
- MySQL with persistent storage using Docker volumes
- Static files served via Nginx
- Environment-based configuration using .env
- Secure setup (no public DB exposure)
- Jenkins pipeline for automated build and deployment

---

## 🚀 Setup & Run

git clone https://github.com/rajnavneet9931/django-notes-app-devops.git
cd django-notes-app-devops

docker compose up -d --build

---

## 🌐 Access

http://<your-ec2-public-ip>

---

## 🔄 Jenkins Pipeline

Pipeline stages:
- Checkout Code
- Build Containers
- Deploy Containers
- Verify Running Containers

---

## 🧠 Key Learnings

- Debugged 502 Bad Gateway issues
- Fixed Docker networking (service names)
- Managed environment variables correctly
- Used Gunicorn + Nginx for production setup
- Implemented CI/CD with Jenkins

---

## 👨‍💻 Author

Raj Navneet  
GitHub: https://github.com/rajnavneet9931
