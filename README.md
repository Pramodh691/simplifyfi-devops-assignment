 Simplifyfi DevOps Assignment

This repository contains a DevOps assignment demonstrating Dockerization of a backend and frontend application.

 Project Structure
- backend: Node.js backend service
- frontend: Static frontend served using Nginx

 Backend
- Node.js application
- Dockerized using Node Alpine
- Runs on port 3000

 Frontend
- Static HTML
- Served using Nginx
- Runs on port 80

 Docker Commands

 Backend
```bash
docker build -t backend-app .
docker run -p 3000:3000 backend-app

 Frontend
docker build -t frontend-app .
docker run -p 8080:80 frontend-app
