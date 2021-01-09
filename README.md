### Django Backend Template

This is a django backend template, with presets necessary for API development.
Note: I use Visual Studio Code. It should work in any other IDE too

## Getting Started

# Installations
- Install Python
- Install Django
    `pip install django`
- Install Django Rest Framework
    `pip install django-rest-framework`
- Install Django Rest Swagger
    `pip install django-rest-swagger`
- Install drf-yasg
    `pip install drf-yasg`


Whoosh!! That's a lot of installation. 
No worries, it's a one time thing.

# Working with the Template

- Clone the repo

- Edit models

_Run the following commands inside the specific app folder(employeeApp), not project folder._
- Create superuser
    `python manage.py createsuperuser`

- Make migrations
    `python manage.py makemigrations`

- Migrate
    `python manage.py migrate`

- Run server
    `python manage.py runserver`

# Accesing the API Documentation

Go to: _yoururl.com:port/docs_
If you wish to change the url, edit the _urls.py_ file in the project directory.

Have fun!
