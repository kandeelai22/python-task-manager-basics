# 🚀 GitHub Publishing Guide – Task Manager Project

This file is a complete checklist and copy-paste guide
for publishing the Task Manager project on GitHub.

Author: Ahmed Kandeel

---

## 1️⃣ Recommended Repository Structure

```
task-manager/
│
├── json_version/
│   ├── task_manager.py
│   └── tasks.json
│
├── oop_version/
│   ├── task_manager_oop.py
│   └── tasks.json
│
├── sqlite_version/
│   └── task_manager_sqlite.py
│
├── .gitignore
├── README.md
└── LICENSE
```

---

## 2️⃣ README.md (Main Repository README)

```md
# 📝 Task Manager (Python)

A simple console-based **Task Manager** written in Python.  
The project demonstrates **three different approaches** to building the same application.

## 🚀 Versions Included

### 1️⃣ JSON Version (Functional)
- Procedural programming style
- Data stored in JSON file
- Good for beginners

### 2️⃣ JSON Version (OOP)
- Object-Oriented Programming
- Clean structure using classes
- Better scalability

### 3️⃣ SQLite Version (Database)
- Uses SQLite for persistent storage
- SQL queries and real database handling
- Suitable for real-world applications

---

## ✨ Features
- Add tasks (with optional notes)
- View all tasks
- Mark tasks as completed
- Rename tasks
- Remove tasks
- Persistent data storage

---

## 🛠 Requirements
- Python **3.10+**
- No external libraries required

---

## ▶️ How to Run

### JSON Version
```bash
python json_version/task_manager.py
```

### OOP Version
```bash
python oop_version/task_manager_oop.py
```

### SQLite Version
```bash
python sqlite_version/task_manager_sqlite.py
```
---
🎯 Purpose of This Project :

Practice Python fundamentals

Understand differences between programming paradigms

Build a strong programming foundation

Serve as a beginner-friendly reference project

---

## 👨‍💻 Author
**Ahmed Kandeel**
```

---

## 3️⃣ .gitignore File

```gitignore
__pycache__/
*.pyc
*.pyo
*.db
*.sqlite3
tasks.json
.env
.venv
```

---

## 4️⃣ LICENSE (MIT)

```text
MIT License

Copyright (c) 2026 Ahmed Kandeel
```

---

## 5️⃣ GitHub Repo Description

A Python Task Manager built using three approaches: Functional, OOP, and SQLite Database.

---

## 6️⃣ GitHub Topics

python, task-manager, sqlite, json, oop, beginner-project, cli-app, learning-project

---

## 7️⃣ Git Commands

```bash
git init
git add .
git commit -m "Initial project structure"
git commit -m "Add JSON-based task manager (functional)"
git commit -m "Add OOP-based task manager"
git commit -m "Add SQLite database version"
git commit -m "Add README and documentation"
```
