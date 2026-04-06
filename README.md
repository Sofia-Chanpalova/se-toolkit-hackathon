# TaskTracker

Dead‑simple task tracker for procrastinating students.

## Demo

![Скриншот](screenshot.png)

## Product context

**End user:** Procrastinating student

**Problem:** Student does not need to memorize all his tasks — he forgets them and loses track of what's done.

**Solution:** A web app where a student writes all his tasks and marks them done.

## Features

### Implemented
- ✅ Add new task (Version 1)
- ✅ Mark task as done (Version 2)
- ✅ Tasks split into "Active" and "Completed"
- ✅ Persistent storage in PostgreSQL
- ✅ Docker containerization

### Not yet implemented
- ❌ Deadlines and due dates
- ❌ User authentication
- ❌ Edit and delete tasks

## Tech stack

- **Backend:** FastAPI (Python)
- **Database:** PostgreSQL 15
- **Frontend:** HTML + Jinja2 templates
- **Containerization:** Docker + docker-compose
- **Deployment:** Ubuntu 24.04 VM

## Usage

1. Open `http://<VM_IP>:8000` in your browser
2. Type a task and click "➕ Добавить"
3. Click "✅ Выполнено" to mark a task as done
4. Refresh the page — all tasks persist

## Deployment

### Prerequisites
- OS: Ubuntu 24.04
- Installed: Docker, docker-compose
