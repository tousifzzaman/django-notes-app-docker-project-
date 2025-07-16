# 📝 Django Notes App (Dockerized)

A production-ready, fully Dockerized Notes Management Web App using **Django**, **MySQL**, and **Nginx**. This project is ideal for learning full-stack web development, containerization, and building scalable apps.

---

## 🚀 Features

- ✍️ Create, edit, and delete notes
- 🐳 Docker + Docker Compose for easy setup
- 🔐 Environment variables via `.env` file
- 🗃️ MySQL volume for persistent data
- 🌐 Nginx reverse proxy in front of Gunicorn

---

## 🧰 Tech Stack

- Django + Gunicorn
- MySQL (with Docker volume)
- Nginx (as a reverse proxy)
- Docker & Docker Compose

---

## 🛠️ Getting Started

### 📦 1. Clone the Repository

```bash
git clone https://github.com/tousifzzaman/django-notes-app.git
cd django-notes-app
🔑 2. Add Environment Variables
cp .env.example .env
🐳 3. Run the App
docker compose up --build

