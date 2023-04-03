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

use npm init -y to create package.json
use npm i webpack webpack-cli --save-dev to get package-lock.json

use npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev

npm i react react-dom --save-dev   to install react

npm  install @material-ui/core --force
npm install @babel/plugin-proposal-class-properties --force
