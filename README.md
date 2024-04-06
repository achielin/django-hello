# django-hello
#create a directory and cd to it
#create a virtual env -python3 -m venv myenv
#activate the virtual env - source myenv/bin/activate then cd to it
#install django inside your venv - pip install django
#start the project using - django-admin startproject myproject
#run server - python manage.py runserver
#create an app -django-admin startapp myapp and cd to the app
#navigate to settings under apps ,add your app
#go to views.py and import http and define it;
from django.shortcuts import render
from django.http import HttpResponse

# Create your views here.
def hello(request):
    return HttpResponse('Hello world! Welcome to my first Django Website')

#navigate to your app and create a urls.py file and import path and views
#go to urls.py in your project and and copy the path of your app