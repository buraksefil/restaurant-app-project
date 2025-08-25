Restaurant App Project

A simple restaurant web application with a frontend, backend API, and reverse proxy using Docker Compose and HAProxy.

🚀 Stack

Frontend: SPA (client)

Backend: REST API (backend)

Proxy: HAProxy for / (frontend) and /api (backend)

Orchestration: Docker Compose

▶️ Run Locally
docker compose up --build


Frontend: http://localhost

API: http://localhost/api

🧩 Project Structure
restaurant-app-project/
├─ backend/      # API source
├─ client/       # Frontend source
├─ haproxy.cfg   # Reverse proxy config
└─ docker-compose.yml

📌 Description

What: Built a containerized restaurant web app.
How: Orchestrated frontend & backend with Docker Compose, configured HAProxy for single-domain access.
Impact: Simplified local development and deployment with one command, ensuring clean routing and scalability.
