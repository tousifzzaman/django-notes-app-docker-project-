# 📝 Django Notes App – Dockerized with MySQL & Nginx

A production-ready **Django Notes App**, fully Dockerized using **Gunicorn**, **MySQL**, and **Nginx**.  
Built and containerized by [Tousif Zzaman](https://github.com/tousifzzaman).

---

## 🚀 Features

- 🐍 Django backend with admin panel
- 🐳 Docker + Docker Compose setup
- 🧱 MySQL database with volume persistence
- 🌐 Nginx reverse proxy server
- 🔥 Gunicorn WSGI server for production
- ♻️ Auto-restart and healthcheck configs
- 📦 Environment variables support via `.env`

---

## 🛠️ Tech Stack

- Python 3
- Django
- Docker & Docker Compose
- MySQL
- Nginx
- Gunicorn

---

## 🧰 Getting Started

### 🔧 Clone the repo

```bash
git clone https://github.com/tousifzzaman/django-notes-app-docker-project-.git
cd django-notes-app-docker-project-
🛠️ Create a .env file
DEBUG=False
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=*
DB_HOST=db
DB_NAME=test_db
DB_USER=root
DB_PASSWORD=root
🐳 Run the project
docker compose up --build
Open in browser: http://your-ec2-ip
Admin: http://your-ec2-ip/admin

📂 Project Structure
.
├── nginx/
│   └── default.conf
├── notesapp/
│   └── Django app files
├── Dockerfile
├── docker-compose.yml
├── .env
└── README.md

