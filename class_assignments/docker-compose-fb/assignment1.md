````md
# Multi-Service Frontend and Backend Setup Using Docker Compose

## 📌 Assignment: Frontend & Backend Setup Using Docker Compose

This assignment helps you understand how **Frontend and Backend services** run together using **Docker Compose**, share a network, use **port binding**, and persist data with **Docker volumes**.

---

## 🧠 Objective

Create a **multi-service application** where:
- One **Frontend** service
- One **Backend** service  
run together and **communicate with each other** inside the same Docker network.

---

## 📝 The Task

Create a simple setup with:
- One **Frontend service**
- One **Backend service**

---

## ✅ Requirements

Your solution must:
- Use **Docker Compose**
- Use **Port Binding**
- Define **both services in one `docker-compose.yml`**
- Include **Docker Volumes**
- Ensure **Frontend ↔ Backend communication** on the same network

---

## 🧩 Key Concepts Covered

- Docker Compose  
- Multi-container applications  
- Container networking  
- Port binding  
- Docker volumes  
- Service-to-service communication  

---

## 🗂️ Suggested Folder Structure

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
````

---

## 🚀 How to Run

```bash
docker compose up --build
```

---

## 🎯 Expected Outcome

* Both services start with **one command**
* Frontend is accessible in the browser
* Frontend successfully communicates with Backend
* Volumes reflect live changes (if mounted)

---

## 🏁 Learning Outcome

After completing this assignment, you will understand:

* How real-world apps use Docker Compose
* How containers talk to each other
* How ports and volumes work in practice

Happy Dockering 🐳🚀

```
```
