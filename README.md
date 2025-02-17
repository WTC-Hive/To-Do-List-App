# Django To-Do List App

A simple Django-based to-do list application that allows users to add, update, and delete tasks. Users can mark tasks as complete and organize their workflow efficiently.

## Features
✅ Add, update, and delete tasks
✅ Mark tasks as completed or pending
✅ User authentication for personalized task management
✅ Due date and priority assignment (Optional)
✅ Responsive UI with Django templates

## Tech Stack
- **Backend:** Django (Python)
- **Database:** SQLite (default), PostgreSQL/MySQL (optional)
- **Frontend:** HTML, CSS (Bootstrap for styling)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/todo-list.git
cd todo-list
```

### 2. Create a Virtual Environment
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Server
```bash
python manage.py runserver
```
Go to **http://127.0.0.1:8000/** to access the application.

## Usage
1. Register or log in to manage tasks.
2. Add new tasks by providing a title and description.
3. Mark tasks as completed once done.
4. Delete tasks that are no longer needed.
