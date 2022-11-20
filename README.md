# Django
En linux, en otro sistema operativo puede que cambie alguna cosa

pip install -r requirements.txt

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

python manage.py migrate (esto al copiarlo en un nuevo dispositivo)


Proyectos:

en http://127.0.0.1:8000/admin/

añadir los siguientes proyectos:

1

    Título: Ecuaciones de Euler-Lagrange

    Descripción: Las ecuaciones de Euler-Lagrange son las condiciones bajo las cuales cierto tipo de problema variacional alcanza un extremo. Aparecen sobre todo en el contexto de la mecánica clásica en relación con el principio de mínima acción, también aparecen en teoría clásica de campos y sirve de base para la formulación de integrales de camino para la teoría cuántica de campos.

    Imagen: /media/braquistocrona.png

    Url: https://www.overleaf.com/project/6191474358451dd787e8b97a

2

    Título: Ecuación de Schrödinger

    Descripción:La ecuación de Schrödinger, desarrollada por el físico austríaco Erwin Schrödinger en 1925, describe la evolución temporal de una partícula subatómica masiva de naturaleza ondulatoria y no relativista. Es de importancia central en la teoría de la mecánica cuántica, donde representa para las partículas microscópicas un papel análogo a la segunda ley de Newton en la mecánica clásica. Las partículas microscópicas incluyen a las partículas elementales, tales como electrones, así como sistemas de partículas, tales como núcleos atómicos.

    Imagen: /media/Schrodingers_cat.png

    Url: https://www.overleaf.com/project/622ca9e94f0174b588bd7f06
