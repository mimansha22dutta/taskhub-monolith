# TaskHub Monolith

A full-stack task management application built using a monolithic architecture, consisting of a React frontend and a FastAPI backend.

The application is containerized with Docker and deployed on Microsoft Azure using Nginx as a reverse proxy and Azure SQL Database as the persistent data store.
---

## Features

- React frontend
- FastAPI REST API
- Azure SQL Database integration
- Dockerized application
- Nginx reverse proxy
- Azure VM deployment

---

## Architecture Overview

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

The application is deployed on Microsoft Azure using Docker containers.
Nginx acts as the reverse proxy, routing requests to the React frontend and FastAPI backend, while Azure SQL Database serves as the persistent data store.

---

## Technology Stack

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

## Repository Structure

```
taskhub-monolith/
│
├── ReactTodoUIMonolith/       
│
├── PyTodoBackendMonolith/       
│
└── README.md
```
---

## Author

**Mimansha Dutta**

Cloud & DevOps Engineer

Building reliable cloud infrastructure, automating deployments, and engineering scalable solutions.


