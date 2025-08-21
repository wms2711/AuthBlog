# Django Blog

A simple blog application built with Django.

## Features

- User authentication (login, logout, register)
- Create, edit, and delete blog posts
- Comment on posts

## Requirements

- Python 3.8+
- Django 4.x
- SQLite (default) or other database

## Setup

1. Clone the repository:
    ```bash
    git clone <this project URL>
    cd django_project
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```bash
    python manage.py runserver
    ```

7. Visit [http://localhost:8000/](http://localhost:8000/) in your browser for running in dev.

## Project Structure

```
django_project/
├── blog/           # Blog app
├── django_project/ # Project settings
├── manage.py
└── requirements.txt
```