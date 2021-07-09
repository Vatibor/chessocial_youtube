# chessocial_youtube
##
- python-django
- html, js, bootstrap

## cmd parancsok
- django-admin startproject chesssocial .
- python manage.py startapp chesssocial_app
- python manage.py migrate
- python manage.py runserver
### adatbázis migrálása
- python manage.py makemigrations
- python manage.py migrate
### cmd-s lépésrögzítés
- python manage.py shell
- from chesssocial_app.models import Position
- p = Position()
- p.save
## admin létrehozása
- python manage.py createsuperuser
- host/admin