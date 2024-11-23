”Health is wealth” Obviously, you have heard it a thousand times but as we grow older we often realize it’s true and this app provides an interesting way to get started with the very boring term “dieting” as we already know “FITNESS START WITH WHAT WE EAT”.

Let’s develop an interesting project – Calorie Calculator to record and estimate number of calories we need to consume daily.
This is a calorie counter app made with Django. 

Requirements:

Python (I am using version 3.8.2)
Django(I am using version 3.1)
Django-filter

mkdir calorieapp
cd calorieapp

pipenv install Django
breakdown structure of Django...

settings.py: Contains project-wide settings, such as database configurations, secret keys, and installed apps.   
urls.py: Defines URL patterns and maps them to specific views.   
wsgi.py: Entry point for WSGI-compatible web servers.
models.py: Defines database models.   
views.py: Contains view functions to handle requests and render templates.   
templates directory: Stores HTML templates.   
static directory: Stores static files like CSS, JavaScript, and images.   
media directory: Stores user-uploaded files.   


pipenv shell
(calorieapp-kub3HwmJ) django-admin startproject calorie_app .
(calorieapp-kub3HwmJ)python manage.py startapp calories

(calorieapp-kub3HwmJ) pip install django-filter

to run on the server use the command on terminal:
py manage.py runserver

