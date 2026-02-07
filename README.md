# 🚀 MERN Stack Containerized Using Docker Compose

---

## 📌 Project Overview

This project demonstrates how to containerize a **MERN (MongoDB, Express, React, Node.js)** application using **Docker Compose**.

The application is fully containerized and can be started using a single command with Docker Compose.

---

## 🏗️ Tech Stack

- **Frontend:** React (Vite)  
- **Backend:** Node.js + Express  
- **Database:** MongoDB (Official Docker Image)  
- **Containerization:** Docker  
- **Orchestration:** Docker Compose  
- **Networking:** Custom Docker Bridge Network  

---

## 🐳 Docker Architecture

This project uses:

- Separate containers for:
  - Frontend
  - Backend
  - MongoDB
- Custom Docker Network → `mern`
- Persistent MongoDB storage using Docker volumes

---

## 🌐 Docker Network

A custom bridge network is used so containers can communicate using service names.
- Custom Docker Network → `mern`

---

## 💾 Persistent Data Storage

MongoDB data is stored using **Docker volume mapping** to ensure data is not lost when containers stop or are removed.



