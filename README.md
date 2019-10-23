## Example
Re create chat app from Django Private Chat
https://github.com/Bearle/django-private-chat

## Virtual Environmant
$ virtualenv venv
$ virtualenv -p /usr/bin/python3 venv
$ source venv/bin/activate

## Setup Django
$ pip install Django
$ django-admin startproject mysite
$ cd mysite
$ python manage.py runserver 0.0.0.0:8000

## New app
$ python manage.py startapp chat