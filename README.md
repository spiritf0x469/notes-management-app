# Notes Management App

A Flask-based web application for managing personal notes with user authentication and secure data storage.

---

## 🚀 Features

* User registration and login system
* Secure authentication using Flask-Login
* Create, view, and delete personal notes
* User-specific note storage (each user sees only their own notes)
* Session-based login management

---

## 🛠️ Tech Stack

* Flask
* Flask-Login
* Python
* SQLite
* SQLAlchemy
* HTML (Jinja2 templates)
* CSS
* JavaScript

---

## 📁 Project Structure

* `main.py` → Entry point of the application
* `templates/` → HTML files (login,signup,base,etc.)
* `static/` → CSS/JS files
* `instance/` → SQLite database storage

---

## ⚙️ How to Run Locally

### 1. Clone the repository

```bash id="n1q8kd"
git clone https://github.com/your-username/notes-management-app.git
cd notes-management-app
```

---

### 2. Create virtual environment

```bash id="k2m8qe"
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate  # Mac/Linux
```

---

### 3. Install dependencies

```bash id="p9x3ld"
pip install flask flask-login flask-sqlalchemy
```

---

### 4. Run the application

```bash id="s7v2mq"
py main.py
```

---

### 5. Open in browser

```
http://localhost:5000
```

---

## 📌 Notes

* First, create an account to access notes
* Each user has isolated personal notes
* Database file is created automatically inside `instance/` folder
* Keep `main.py` in the root directory while running

---

## 💡 Learning Outcomes

* User authentication with Flask-Login
* Session management
* Database integration with SQLAlchemy
* Server-side rendering using Flask templates
* Full-stack web development fundamentals
