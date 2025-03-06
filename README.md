# Modern Task Manager

A full-featured task management application built with Django that includes a modern UI and complete CRUD functionality.

## Features

- **Create, Read, Update, Delete (CRUD)** operations for tasks
- **Search functionality** to quickly find tasks
- **Filter tasks** by status (Pending, In Progress, Completed)
- **Responsive design** that works on desktop and mobile devices
- **Modern card-based UI** with status indicators and priority highlighting
- **Interactive elements** like dropdowns, tooltips, and status badges
- **Form validation** with helpful error messages
- **Date picker** for easy due date selection
- **Pagination** for handling large numbers of tasks

## Project Structure

```
task_manager/
├── task_manager/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── tasks/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── migrations/
│   └── templates/
│       └── tasks/
│           ├── base.html
│           ├── task_confirm_delete.html
│           ├── task_form.html
│           └── task_list.html
├── manage.py
└── README.md
```

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Visit `http://127.0.0.
