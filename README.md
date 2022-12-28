# Django with Poetry Sample Project

This is a sample project to show how to use Poetry with Django.

## Simple Steps

1. Install Poetry: <https://python-poetry.org/docs/#installation>
2. `poetry init`
3. `poetry config virtualenvs.in-project true --local`
4. `poetry add django`
5. `echo ".venv" >> .gitignore`
6. `poetry run django-admin startproject django_project .`
7. `poetry shell`
8. `poetry run python -m django --version`
9. `poetry run python manage.py migrate`
10. `poetry run python manage.py createsuperuser`
11. `poetry run python manage.py runserver 8080`

Access the admin page at <http://localhost:8080/admin/>

## Polls app

1. `poetry run python manage.py startapp polls`
