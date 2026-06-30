# 📝 notes management app

a flask-based web application for managing personal notes with user authentication and secure data storage. this project was built to learn user authentication, session management and database integration using flask.

## ✨ features

* 🔐 user registration and login system
* 🛡️ secure authentication using flask-login
* 📝 create, view and delete personal notes
* 👤 user-specific note storage (each user can access only their own notes)
* 🔄 session-based login management

## 🛠️ tech stack

### ⚙️ backend

* flask
* flask-login
* python
* sqlalchemy

### 🗄️ database

* sqlite

### 🎨 frontend

* html (jinja2 templates)
* css
* javascript

## 📂 project structure

```text
notes-management-app
├── instance
│   └── database.db
├── static
│   ├── css
│   └── js
├── templates
│   ├── base.html
│   ├── home.html
│   ├── login.html
│   └── signup.html
├── main.py
└── requirements.txt
```

## ⚙️ installation

### 1️⃣ clone the repository

```bash
git clone https://github.com/spiritf0x469/notes-management-app.git
cd notes-management-app
```

### 2️⃣ create a virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ install dependencies

```bash
pip install flask flask-login flask-sqlalchemy
```

### 4️⃣ run the application

```bash
python main.py
```

### 5️⃣ open in your browser

```text
http://127.0.0.1:5000
```

## 👨‍💻 author

**sameer sainii**
