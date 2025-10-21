python3 -m venv .venv
source .venv/bin/activate
pip install django
django-admin startproject config .
python3 manage.py startapp app 
python3 manage.py migrate     
python3 manage.py runserver
