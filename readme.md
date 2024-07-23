# Social Media Project Setup Guide

## 1. Create a Django Project

In the project directory, create a new Django project:

```bash
django-admin startproject social_media
cd social_media
django-admin startapp core
python3 -m venv venv
source venv/bin/activate
pip install django
python3 manage.py runserver
python3 -m django --version
python3 -m pip install Pillow
python3 manage.py makemigrations
python3 manage.py createsuperuser
(Username (leave blank to use 'tina'): admin
Email address: admin@socialbook.com
password:admin)

python3 manage.py makemigrations
python3 manage.py migrate
```
