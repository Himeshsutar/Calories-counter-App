This is a calorie counter app made with Django. 
Requirements:

Python (I am using version 3.8.2)
Django(I am using version 3.1)
Django-filter

mkdir calorieapp
cd calorieapp

pipenv install django
models.py: Accessing table in the database.
urls.py: Location for each files in browser.
views.py: request response at https server.
migrations: Managing database.

pipenv shell
(calorieapp-kub3HwmJ) django-admin startproject calorie_app .
(calorieapp-kub3HwmJ)python manage.py startapp calories

(calorieapp-kub3HwmJ) pip install django-filter

