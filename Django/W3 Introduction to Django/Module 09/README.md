## MVT

Model View Template

1. Views: Contains various methods.
2. Model: Database.
3. Template: Frontend or client side.

## Virtual environment

A dedicated and isolated place for creating a project, where the packages don't access to the outer environment and vice versa.

1. Creating and naming virtual environment: `python -m venv name`
2. Activating virtual environment: `name\Scripts\activate`
3. To deactivate: `deactivate`

## Creating Django project

0. Install django in the virtual environment: `pip install django`
1. Command: `django-admin startproject name`
2. Go the django project folder: `cd name`
3. Run the project: `python manage.py runserver`