# Django
En linux, en otro sistema operativo puede que cambie alguna cosa
conda create -n django2 python
activate django2
    pip install django (ya debería estar instalado)
    python -m django --version
django-admin startproject webpersonal (en el creado por Railway no hay que hacerlo)
python manage.py runserver (para ejecutar la página)

Ejecutar:
vas a root (sudo -s)
su postgres
psql
alter user postgres with password 'albertopostgres';
CREATE DATABASE railway WITH OWNER postgres;
