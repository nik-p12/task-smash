# ✅ Task Smash 2.0

**Task Smash 2.0** is a simple and lightweight task management (To-Do list) web application built with **Flask**, **SQLAlchemy**, and **SCSS**. It allows you to add, edit, and delete tasks through a clean and responsive interface.

---

## 🚀 Features

- Add new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Clean UI with SCSS/CSS styling

---

## 🛠️ Built With

- [Python 3](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)
- [Flask-SCSS](https://github.com/flyforflask/flask-scss)
- SQLite (local database)
- HTML5 + Jinja2 Templates
- SCSS/CSS for styling

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/task-smash.git
cd task-smash
````

### 2. Create a Virtual Environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

The app will be running at: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📁 Project Structure

```
FLASK-START/
│
├── app.py                      # Application principale Flask
├── requirement.txt             # ✅ Fichier des dépendances (pip install -r requirement.txt)
│
├── instance/                   # Contient la base de données SQLite
│   └── database.db
│
├── static/                     # Dossier des fichiers statiques
│   ├── style.css
│   ├── style.css.map
│   └── style.scss              # SCSS source
│
├── templates/                  # Modèles HTML (Jinja2)
│   ├── base.html
│   ├── index.html
│   └── update.html
│
└── env/                        # (optionnel) Environnement virtuel

```
---

## 🧪 How to Use

1. Open the app in your browser.
2. Add a new task using the form.
3. Edit or delete any task using the provided action links.
4. Organize your tasks efficiently!

---

## ✅ Future Improvements

* Add a "Mark as Completed" checkbox
* Task filtering (completed vs. pending)
* PostgreSQL or MySQL database support
* Flash messages for feedback on actions

---

## 👤 Author

Developed by **\nik-p12**

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

````

---

### ✅ Bonus: `requirements.txt`