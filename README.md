📝 Todo App - Django

A simple Todo List web application built with Django that allows users to create, update, and delete tasks.

https://github.com/achyuthjoshi07/todoapp/blob/f211dd063e875034ef3e5195cb94e2db70444456/OP.png
🚀 Features
-> Add new tasks
-> View all tasks
-> Mark tasks as completed
-> Edit existing tasks
-> Delete tasks
-> User-friendly interface
Django-based backend
🛠️ Technologies Used
-> Python
-> Django
-> HTML
-> CSS

📂 Project Structure
todo-app/
│
├── todo/
│   ├── migrations/
│   ├── templates/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
├── manage.py
└── db.sqlite3

## ⚙️ Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to project directory
cd todo-app

# Create virtual environment
python -m venv env

# Activate virtual environment

# Windows
env\Scripts\activate

# Linux/Mac
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver
```

Open your browser and visit:


http://127.0.0.1:8000/
📸 Application Workflow
Add a new task.
View the task list.
Update task status when completed.
Edit task details if needed.
Delete tasks that are no longer required.
🎯 Learning Outcomes
Understanding Django Models, Views, and Templates (MVT)
URL routing in Django
Database operations using Django ORM
Form handling and CRUD operations
Basic web application development
