python -m venv venv
source venv/Scripts/activate
pip install django
django-admin startproject djangocrud .
python manage.py runserver
python manage.py startapp tasks


python manage.py migrate
python manage.py makemigrations

python manage.py shell
exit()

python manage.py runserver

python manage.py createsuperuser

rm -rf .git