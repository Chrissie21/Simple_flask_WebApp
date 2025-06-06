# 📝 Flask Notes Web App

A simple, secure notes web application built with **Flask** to demonstrate backend development skills including user authentication, form handling, database modeling, and RESTful routing. Users can register, log in, add notes, and delete them. The app uses **Flask-Login** for session management and **Bootstrap 4** for styling.

---

## 🚀 Features

- 🔐 **User Authentication**
  - Register & securely log in
  - Passwords hashed using PBKDF2 (`generate_password_hash`)
  - Login required to access main functionality

- 🗒️ **Notes CRUD**
  - Create and save personal notes
  - Delete notes using dynamic JavaScript + Flask route

- 🧱 **MVC Structure**
  - Flask Blueprints (`auth`, `views`) for clean modular code
  - SQLAlchemy ORM models: `User`, `Note`

- 🎨 **Frontend**
  - Responsive UI with Bootstrap 4
  - Conditional rendering with Jinja templates
  - Flash messages for feedback (success/error)

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Flask**
- **Flask-Login**
- **Flask SQLAlchemy**
- **Jinja2 Templates**
- **Bootstrap 4**
- **SQLite (default DB)**

---


---

## 🔧 Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/Chrissie21/Simple_flask_WebApp.git
cd Simple_flask_WebApp
```

2. **Create a VirtualEnv**
```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. **Istall Requirements**
```bash
pip install -r requirements.txt
```

4. **Run the flaskApp**
```bash
flask run
```

5. Visit http://127.0.0.1:5000/ in your browser.