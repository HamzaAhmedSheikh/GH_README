# 🚀 Multi-Service Frontend & Backend Setup Using Docker Compose

## 📌 Assignment Overview

This assignment is designed to help you understand how **Frontend** and **Backend** services work together using **Docker Compose**.

You will learn how multiple services:

* Run together with a single command
* Share the same Docker network
* Communicate with each other
* Use **port binding** and **Docker volumes** in a real-world setup

## 🧠 Objective

The goal of this assignment is to create a **multi-service application** where:

* One **Frontend service**
* One **Backend service**

run together using **Docker Compose** and communicate inside the **same Docker network**.

---

## 📝 Task Description

You need to create a simple project that includes:

* A **Frontend service** (any framework or static app)
* A **Backend service** (API or simple server)

Both services must be defined and managed using **Docker Compose**.

---

## ✅ Requirements

Your solution **must** meet the following requirements:

* Use **Docker Compose**
* Use **port binding** to expose services
* Define **both Frontend and Backend** in a single `docker-compose.yml` file
* Use **Docker volumes** (for persistence or live reload)
* Ensure **Frontend ↔ Backend communication** within the same Docker network

---

## 🧩 Key Concepts Covered

By completing this assignment, you will practice:

* Docker Compose
* Multi-container applications
* Container-to-container networking
* Port binding
* Docker volumes
* Service-to-service communication

---

## 🗂️ Suggested Project Structure

```text
docker-compose-fb/
│
├── frontend/
│   ├── Dockerfile
│   └── app/
│
├── backend/
│   ├── Dockerfile
│   └── app/
│
├── docker-compose.yml
└── README.md
```

> 💡 You can change the folder structure if needed, but this layout is recommended for clarity.

---

## 🚀 How to Run the Project

Make sure Docker and Docker Compose are installed, then run:

```bash
docker compose up --build
```

This single command will:

* Build images for both services
* Start Frontend and Backend containers
* Create a shared Docker network

---

## 🎯 Expected Outcome

After running the project:

* ✅ Both services start using **one command**
* 🌐 Frontend is accessible in the browser
* 🔁 Frontend successfully communicates with the Backend
* 💾 Docker volumes reflect live changes (if mounted)

---

## 🏁 Learning Outcome

After completing this assignment, you will clearly understand:

* How real-world applications use **Docker Compose**
* How multiple containers communicate with each other
* How **ports** and **volumes** work in practice
* How Frontend and Backend services are connected

---

Happy Dockering 🐳🚀
Keep building & keep shipping 💪

---
