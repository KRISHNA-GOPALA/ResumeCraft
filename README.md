# ResumeCraft

A Django-based web application to help you create and showcase your digital resume. This project enables users to build their resume dynamically and display it in a professional format.

## Features

- Create, edit, and update resume information.
- Store data in a database for persistence.
- User-friendly interface for resume customization.
- Export resume to PDF (if implemented).
- Easy deployment with Django.

## Requirements

Ensure you have Python installed (version 3.6+ recommended). Install dependencies using:

```bash
pip install -r requirements.txt
```

## Installation & Setup
### Clone the repository:

```bash
git clone https://github.com/bobby-didcoding/resume_app.git
cd resume_app
```

### Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Apply database migrations:
```bash
python manage.py migrate
```

### Create a superuser (optional, for admin access):
```bash
python manage.py createsuperuser
```

### Run the development server:
```bash
python manage.py runserver
```

### Open the application in your browser:
``` bash
http://127.0.0.1:8000/
```

## Deployment
To deploy the application, configure the following:

1. Set up a production database (e.g., PostgreSQL).
2. Configure environment variables for settings.
3. Use a production-ready WSGI server (e.g., Gunicorn).
4. Set up a web server (e.g., Nginx).
5. Use Docker (if needed) for containerized deployment.
