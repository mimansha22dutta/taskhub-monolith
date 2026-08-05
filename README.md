# 🚀 TaskHub Monolith

A modern full-stack task management application built using a **monolithic architecture**, featuring a responsive React frontend and a high-performance FastAPI backend.

The application is fully containerized with Docker and deployed on **Microsoft Azure**, using **Nginx** as a reverse proxy and **Azure SQL Database** as the backend data store. The project demonstrates modern DevOps practices, cloud deployment, and scalable application architecture.

---

## ✨ Features

- Responsive React-based user interface
- High-performance FastAPI backend
- RESTful API architecture
- Azure SQL Database integration
- Secure database connectivity using `pyodbc` and ODBC Driver 18
- Dockerized frontend and backend services
- Nginx reverse proxy configuration
- Cloud deployment on Microsoft Azure Virtual Machine
- Production-ready project structure

---

## 🏗️ Architecture

```
                Client
                   │
                   ▼
              Nginx Reverse Proxy
                   │
        ┌──────────┴──────────┐
        ▼                     ▼
 React Frontend        FastAPI Backend
                               │
                               ▼
                    Azure SQL Database
```

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React, JavaScript, HTML, CSS |
| Backend | FastAPI, Python |
| Database | Azure SQL Database |
| Containerization | Docker |
| Web Server | Nginx |
| Cloud | Microsoft Azure Virtual Machine |
| Database Connectivity | pyodbc, ODBC Driver 18 |

---

## 📁 Repository Structure

```
taskhub-monolith/
│
├── ReactTodoUIMonolith/          # React Frontend
│
├── PyTodoBackendMonolith/        # FastAPI Backend
│
└── README.md
```

---

## 📂 Project Components

### 🔹 ReactTodoUIMonolith

Contains the React-based frontend application responsible for the user interface, authentication flow, and interaction with backend APIs.

### 🔹 PyTodoBackendMonolith

Contains the FastAPI backend application responsible for business logic, REST APIs, database operations, and Azure SQL connectivity.

---

## ☁️ Deployment

The application is deployed on **Microsoft Azure Virtual Machine** using Docker containers.

Deployment architecture includes:

- Docker Containers
- Nginx Reverse Proxy
- FastAPI Backend
- React Frontend
- Azure SQL Database

---

## 👩‍💻 Author

**Mimansha Dutta**

Cloud & DevOps Engineer

Building reliable cloud infrastructure, automating deployments, and engineering scalable solutions.


