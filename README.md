# example.django.sass

Example for using sass files support for Django Framework

## Install

$ virtualenv --python=/usr/bin/python3 venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
$ python manage.py migrate
$ python manage.py createsuperuser --username admin --email admin@mail.com

## Run

$ python manage.py runserver 0.0.0.0:8000
