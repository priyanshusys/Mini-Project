# 🚀 Mini-Project — Job Allotment System

> Simple full-stack web app for managing job allotments (admin + user roles).

## 📝 Overview
This repository contains a small job allotment system built with Python and HTML (Django/Flask-style structure). It provides role-based login, job creation/allocation, reporting and status tracking through a web interface.

## ⭐ Features
- Admin and User roles
- Login / authentication
- Job creation, allocation and status updates
- Report submission and tracking
- Static assets and HTML templates included

## 🛠️ Tech Stack
- Python (back-end)
- HTML templates (frontend)
- Static assets (CSS / JS / images)

> Files included: `manage.py`, `main.py`, `pyproject.toml`, `core/`, `jobmanage/`, `templates/`, `static/`.

## ⚡ Quick Start (Development)
1. Clone the repo:

```bash
git clone https://github.com/priyanshusys/Mini-Project.git
cd Mini-Project
```

2. Create and activate virtual environment:

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3. Install dependencies (if using pip and `pyproject.toml` provides them):

```bash
pip install -r requirements.txt  # or use poetry if configured
```

4. Run migrations (if Django) and start server:

```bash
# Django
python manage.py migrate
python manage.py runserver

# Or if app runs via main.py
python main.py
```

Open http://127.0.0.1:8000 in your browser.

## 📂 Project Structure
- `core/` — core app logic
- `jobmanage/` — job management app
- `templates/` — HTML templates
- `static/` — CSS, JS, images
- `manage.py` / `main.py` — entry points

## 🤝 Contributing
Feel free to open issues or pull requests. Add clear commit messages and keep PRs focused.

## 📌 Notes / TODO
- Add a `requirements.txt` or Poetry setup for reproducible installs
- Provide sample data or an initial admin user creation script
- Add README badges (tests, license) if needed

## 📄 License
Add a license file (e.g., MIT) if you want to open-source the project.

