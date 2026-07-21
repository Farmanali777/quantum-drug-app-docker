# 🚀 Quantum Drug Discovery App (Docker)

This project provides a **Dockerized Flask-based Quantum Drug Discovery application** that can be easily pulled and run from Docker Hub.

## 📋 Prerequisites

Before running the application, ensure the following are installed:

- Docker
- Git (optional, for cloning the repository)

---

## 🐳 Docker Image

**Docker Hub Repository:**
👉 https://hub.docker.com/r/farman1/quantum-drug-app

---

## ⚙️ How to Run

### 1️⃣ Pull the Docker Image

```bash
docker pull farman1/quantum-drug-app:latest
docker images
```

### 2️⃣ Run the Container

```bash
docker run -d -p 8080:8000 --name quantum-app farman1/quantum-drug-app:latest
```

### 3️⃣ Access the Application

Open your browser:

```text
http://localhost:8080
```

> **Note:**
> - If running the Docker container on an **AWS EC2** instance, allow inbound **TCP port 8080** in the EC2 Security Group before accessing the application.
> - If running the container on your **local machine**, no EC2 Security Group configuration is required. Simply open **http://localhost:8080** in your browser.

### 4️⃣ Stop the Container

```bash
docker stop quantum-app
```

### 5️⃣ Remove the Container

```bash
docker rm quantum-app
```
## 📁 Repository Structure

```text
.
├── app.py
├── Dockerfile
├── requirements.txt
├── templates/
├── static/
└── README.md
```


## 📸 Application Screenshots

### 🏠 Home Page

<img width="957" height="534" alt="image" src="https://github.com/user-attachments/assets/15579b26-c78d-4452-9bae-08f843bcc2d1" />

### 📊 Prediction Results

<img width="1039" height="645" alt="image" src="https://github.com/user-attachments/assets/bc890590-a498-4371-ad99-d5c1ca85e902" />

### ✅ Active Prediction

<img width="904" height="589" alt="image" src="https://github.com/user-attachments/assets/99b801e1-7c33-43f6-93af-0514ec992192" />

### ❌ Inactive Prediction

<img width="935" height="615" alt="image" src="https://github.com/user-attachments/assets/f05011d2-ca68-4b9a-9309-19a50ae952fa" />

### ⚠️ Invalid Input Validation

<img width="857" height="550" alt="image" src="https://github.com/user-attachments/assets/4520c66e-f749-4ed8-b439-9c8920e5f4bc" />

## 🧱 Features

- Flask-based Quantum Drug Discovery web application
- Fully containerized using Docker
- Simple one-command deployment
- Consistent execution across environments
- Ready for Kubernetes deployment

## 🛠️ Technologies Used

- Python
- Flask
- Docker
- Linux

 
## 🎯 Use Case

This project demonstrates how to:

- Package a Flask application into a Docker container
- Publish container images to Docker Hub
- Run applications consistently across different environments
- Prepare applications for Kubernetes deployment


## ☸️ Kubernetes Deployment

This application is also deployed on a **multi-node Kubernetes (Kind) cluster** with:

- Deployment (2 replicas)
- NodePort Service
- Persistent Volume (PV)
- Persistent Volume Claim (PVC)

**GitHub Repository:**
👉 https://github.com/Farmanali777/pod-quantum-app


## 👨‍💻 Author

**Farman Ali**

DevOps | Docker | Kubernetes | Cloud

Focused on building production-inspired cloud-native applications using Docker and Kubernetes.

## 📄 License

This project is available under the MIT License.
