# 🎵 Python CLI Playlist Manager — CI/CD with Docker & Jenkins

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue?logo=docker)
![Jenkins](https://img.shields.io/badge/CI%2FCD-Jenkins-red?logo=jenkins)
![Build](https://img.shields.io/badge/Build-Automated-success?logo=github-actions)

A lightweight **Python Command Line Interface (CLI) Playlist Manager** project that demonstrates **CI/CD automation using Jenkins and Docker**.  
It covers the entire development lifecycle — from source code to build, test, containerization, and automated deployment — showcasing real-world **DevOps and Engineering Systems** practices.

---

## 🖼️ Repository Overview

🔗 **GitHub Repository:** [Python-CLI-playlist-manager-with-Docker-Jenkins-CI-CD](https://github.com/Ahadxcode/Python-CLI-playlist-manager-with-Docker-Jenkins-CI-CD)

![Repository Screenshot](https://github.com/Ahadxcode/Python-CLI-playlist-manager-with-Docker-Jenkins-CI-CD/blob/main/screenshot.png)

---

## 🚀 Features

- 🎧 Create, list, shuffle, and export playlists
- 🧩 Fully **Dockerized** app for consistent deployments
- ⚙️ **Jenkins CI/CD pipeline** automates build → test → deploy
- 🧪 Integrated **unit testing (pytest)** and **linting (flake8)**
- 📁 Uses JSON/CSV for playlist persistence
- 🔄 Can be extended to web/ML-based projects (MLOps-ready)

---

## 🧰 Tech Stack

| Category | Tools |
|-----------|--------|
| Language | Python 3.12 |
| CI/CD | Jenkins |
| Containerization | Docker, Docker Compose |
| Version Control | Git & GitHub |
| Testing & Quality | Pytest, Flake8 |
| Deployment | Docker Compose |

---
## 🧩 Project Structure
.
├── tests/ # Unit tests
│ └── test_playlist.py
├── playlist.py # Core CLI logic
├── Dockerfile # Build container image
├── Jenkinsfile # Jenkins pipeline configuration
├── docker-compose.deploy.yml # Docker Compose for deployment
└── README.md


---

## 🏗️ CI/CD Pipeline Workflow

| Stage | Description |
|--------|-------------|
| **1️⃣ Checkout** | Fetch code from GitHub |
| **2️⃣ Lint & Test** | Run Flake8 and Pytest to ensure quality |
| **3️⃣ Build Docker Image** | Create image using Dockerfile |
| **4️⃣ Push Image (Optional)** | Publish to Docker Hub |
| **5️⃣ Deploy** | Run the container via Docker Compose |
| **6️⃣ Cleanup** | Post-build cleanup and notifications |

> 💡 Example: Each commit triggers a Jenkins build → runs tests → builds Docker image → deploys automatically.

---

## 💻 Quick Start Guide

### 🔹 Run Locally
```bash
python playlist.py

🔹 Run with Docker
docker build -t playlist-cli .
docker run --rm playlist-cli

🔹 Run Tests
pytest -v

👨‍💻 Author

Ahad
