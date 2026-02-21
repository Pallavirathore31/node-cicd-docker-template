# 🚀 Node.js CI/CD Docker Template

A production-ready Node.js application with:

- ✅ Docker containerization  
- ✅ GitHub Actions CI/CD  
- ✅ Automatic Docker image build & push  
- ✅ Ready for cloud deployment (Render / Railway / VPS)  

---

## 📌 Project Overview

This repository demonstrates a complete DevOps workflow:

Code → GitHub → CI Pipeline → Docker Build → Docker Hub → Deployment

---

## 🛠 Tech Stack

- Node.js
- Express
- Docker
- GitHub Actions
- Docker Hub

---

## 📁 Project Structure

---

## ⚙️ How It Works

When code is pushed to the `main` branch:

1. GitHub Actions installs dependencies
2. Runs tests
3. Builds Docker image
4. Pushes image to Docker Hub automatically

---

## 🔐 Required GitHub Secrets

Add these in:

| Secret Name        | Value |
|--------------------|-------|
| DOCKER_USERNAME    | Your Docker Hub username |
| DOCKER_PASSWORD    | Docker Access Token |

---

## 🐳 Run Locally With Docker

```bash
docker pull pallavidocker31/node-cicd-template:latest
docker run -p 3000:3000 pallavidocker31/node-cicd-template


## this is the localhost link where code is running 
http://localhost:3000

## this is the responce massage when your project starts running  
{ "message": "CI/CD with Docker is working 🚀" }

## 👩‍💻 Author

Pallavi Rathore  
GitHub: https://github.com/Pallavirathore31  
Docker Hub: https://hub.docker.com/u/pallavidocker31