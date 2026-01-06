create a virtualenvironment python -m venv venv
activate virtual environment venv/Scripts/activate
install django pip install django
create a project django-admin startproject bank_project
go to bank_project cd bank_project
create app python manage.py startapp banking
we have to add app in settings.py at installed apps
we create database in models
we make migrations
python manage.py migrate
python manage.py makemigrations
write views
in urls we want to give a path
finally we can runproject
python manage.py runserver
