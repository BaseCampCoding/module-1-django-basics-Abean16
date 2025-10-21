python3 -m venv .venv
source .venv/bin/activate
pip install django
django-admin startproject config . (config can be any name)
python3 manage.py startapp app (app can be any name)
python3 manage.py migrate     
python3 manage.py runserver
