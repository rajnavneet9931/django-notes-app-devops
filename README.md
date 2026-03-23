# 🚀 Django Notes App (DevOps Project)

## 📌 Overview
This is a production-ready Notes application built using Django and React, containerized with Docker and deployed using a 3-tier architecture.

---

## 🏗 Architecture

Client → Nginx → Gunicorn → Django → MySQL

---

## 🛠 Tech Stack

- Django (Backend)
- React (Frontend)
- Gunicorn (WSGI server)
- Nginx (Reverse proxy + static files)
- MySQL (Database)
- Docker & Docker Compose

---

## ⚙️ Features

- Dockerized multi-container application
- Nginx reverse proxy configuration
- Gunicorn for production-ready serving
- MySQL with persistent storage
- Static files served via Nginx
- Environment-based configuration using `.env`
- Secure setup (no public DB exposure)

---

## 🚀 Setup & Run

```bash
docker compose up -d --build
