# 🍽️ Restaurant App Project

A simple **restaurant web application** built with **Docker Compose** and **HAProxy**, combining a frontend, backend API, and reverse proxy under one setup.

---

## 🚀 Tech Stack
- **Frontend:** SPA (client)  
- **Backend:** REST API (backend)  
- **Proxy:** HAProxy for unified access (`/` → frontend, `/api` → backend)  
- **Orchestration:** Docker Compose  

---

## ▶️ Getting Started
Run the full stack with a single command:

```bash
docker compose up --build

📂 Project Structure

restaurant-app-project/
├─ backend/       # API source code
├─ client/        # Frontend source code
├─ haproxy.cfg    # Reverse proxy configuration
└─ docker-compose.yml

📌 Description

What: Containerized restaurant web app.
How: Orchestrated frontend & backend with Docker Compose, routed traffic via HAProxy.
Impact: One-command deployment with clean routing and scalable architecture.
