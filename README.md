# Simple Django App

This repository contains a basic Django application that demonstrates the fundamental structure and setup of a web application using the Django framework.

## Features

- **Django Project Structure**: Organized structure with a single app (`myapp`).
- **SQLite Database**: Utilizes SQLite as the database backend.
- **Basic App Functionality**: Simple app to demonstrate basic routing and views.
- **Django Admin Interface**: Includes the Django admin interface for model management.

## Project Structure

```plaintext
Simple-Django-App/
│
├── django_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
│   └── ...
│
├── myapp/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── migrations/
│   └── ...
│
├── db.sqlite3
├── manage.py
└── ...
```

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x or newer

### Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/matantoled/Simple-Django-App.git
   cd Simple-Django-App
   ```

2. **Install dependencies**:
   Ensure Django is installed:
   ```
   pip install django
   ```

3. **Run migrations**:
   Apply database migrations:
   ```
   python manage.py migrate
   ```

4. **Run the development server**:
   Start the Django server:
   ```
   python manage.py runserver
   ```

5. **Access the app**:
   Open your browser at `http://127.0.0.1:8000/`.

## Usage

- Access the simple app through the browser.
- Manage models via the Django admin interface at `http://127.0.0.1:8000/admin/` after creating a superuser.
