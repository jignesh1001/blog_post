# Django Girls Blog App

Welcome to the Django Girls Blog App repository! This project is a result of the Django Girls tutorial, designed to help beginners learn web development using the Django framework.

## Features

- **User-Friendly Interface:** Write, edit, and manage articles with ease.
- **Rich Text Editor:** Compose articles using the built-in editor with formatting options.
- **Drafts and Publishing:** Save drafts and publish when ready.
- **Editing:** Easily edit and update published articles.

## Getting Started

1. Clone the repository: `git clone https://github.com/blog_post.git`
2. Navigate to the project directory: `cd blog_post`
3. Create a virtual environment: `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install dependencies: `pip install -r requirements.txt`
6. Configure your database settings in `settings.py`.
7. Apply migrations: `python manage.py migrate`
8. Run the development server: `python manage.py runserver`

## Usage

- Access the admin panel: `http://localhost:8000/admin/`
- Create superuser: `python manage.py createsuperuser`
- Start adding articles through the admin panel.
