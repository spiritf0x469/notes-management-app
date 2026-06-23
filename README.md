# notes management app

a flask-based web application for managing personal notes with user authentication and secure data storage.

---

## features

* user registration and login system
* secure authentication using flask-login
* create,view and delete personal notes
* user-specific note storage (each user sees only their own notes)
* session-based login management

---

## tech stack

* flask
* flask-login
* python
* sqlite
* sqlalchemy
* html (jinja2 templates)
* css
* javascript

---

## project structure

* `main.py` → entry point of the application
* `templates/` → html files (login,signup,base,etc.)
* `static/` → css/js files
* `instance/` → sqlite database storage

---

## how to run locally

### 1. clone the repository

```bash
git clone https://github.com/your-username/notes-management-app.git
cd notes-management-app
```

---

### 2. create virtual environment

```bash
python -m venv venv
venv\scripts\activate   # windows
# source venv/bin/activate  # mac/linux
```

---

### 3. install dependencies

```bash
pip install flask flask-login flask-sqlalchemy
```

---

### 4. run the application

```bash
py main.py
```

---

### 5. open in browser

```text
http://localhost:5000
```

---

## notes

* first,create an account to access notes
* each user has isolated personal notes
* database file is created automatically inside `instance/` folder
* keep `main.py` in the root directory while running

---

## learning outcomes

* user authentication with flask-login
* session management
* database integration with sqlalchemy
* server-side rendering using flask templates
* full-stack web development fundamentals
