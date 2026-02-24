# MEAN DevOps Assignment

## 📌 Project Overview

This project demonstrates containerization and CI/CD implementation for a MEAN stack application.

The application includes:
- Angular frontend
- Node.js + Express backend
- MongoDB database
- Nginx reverse proxy
- Docker & Docker Compose
- CI pipeline using GitHub Actions
- Docker Hub image push automation
- Deployment on AWS EC2

---

## 🏗 Architecture

Client → Nginx → Angular → Node.js API → MongoDB

---

## 🐳 Docker Setup

### Backend
- Dockerized using Node 18 base image
- Exposed on port 8080

### Frontend
- Multi-stage Docker build
- Built with Node
- Served via Nginx

### MongoDB
- Official Mongo image
- Persistent storage

---

## 🐙 Docker Compose

To run locally:

```bash
docker-compose up --build



## CI/CD Pipeline Execution

![CI/CD Success](screenshots/github-actions-success.jpg)

Access application
http://localhost



