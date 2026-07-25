# 🏎️ Apex Motors | Elite Collection (Dockerized)

A containerized high-performance exotic car showcase web application built with HTML5, CSS3, Nginx, and Docker Compose.

---

## 🚀 Features

* **Modern UI/UX:** Dark-mode themed interface styled with CSS Grid, custom variables, and responsive card layouts.
* **Optimized Container:** Built on top of the lightweight `nginx:alpine-slim` image for fast deployments and minimal resource overhead.
* **Production-Ready Compose Setup:** Features resource limits, automated health checks, custom container networking, and auto-restart policies.

---

## 🛠️ Project Structure

```text
.
├── Dockerfile          # Instructions to build the custom Nginx image
├── docker-compose.yml  # Multi-container orchestration & runtime constraints
└── index.html          # Frontend web application code