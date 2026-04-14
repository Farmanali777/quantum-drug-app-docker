# 🚀 Quantum Drug Discovery App (Docker)

This project provides a **Dockerized Flask-based Quantum Drug Discovery application** that can be easily pulled and run from Docker Hub.

---

## 🐳 Docker Image

👉 https://hub.docker.com/r/farman1/quantum-drug-app

---

## ⚙️ How to Run

### 1️⃣ Pull Image
```bash
docker pull farman1/quantum-drug-app:latest

docker images

2️⃣ Run Container
docker run -d -p 8080:8000 --name quantum-app farman1/quantum-drug-app:latest

3️⃣ Access Application
Open in browser:
http://localhost:8080

<img width="957" height="534" alt="image" src="https://github.com/user-attachments/assets/15579b26-c78d-4452-9bae-08f843bcc2d1" />

🧱 Features
Flask-based Quantum Drug Discovery interface
Fully containerized using Docker
Easy deployment with single command
Ready for Kubernetes integration
🛠️ Technologies Used
Python (Flask)
Docker
Linux
🎯 Use Case

This project demonstrates how to:

Package applications into Docker containers
Share applications via Docker Hub
Run applications consistently across environments

## ☸️ Kubernetes Deployment

This app is also deployed on Kubernetes:
👉 https://github.com/Farmanali777/pod-quantum-app
