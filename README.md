# serverlessMusicApp
for assignment3

pip install django 
pip install djangorestfromework

django-admin startproject musicapp
cd musicapp
1. create backend
   
django-admin startapp api

add 'api.apps.ApiConfig' 'rest_framework'in settings.py

if it's the 1st time run the app, use"python ./manage.py makemigrations" to initialize the database.

python ./manage.py migrate

then run the web server by "python ./manage.py runserver"
2. create frontend
   
django-admin startapp frontend 

create folder templates and static
   