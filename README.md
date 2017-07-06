# Bitácora de eventos del usuario by dM

Un modelo "Bitacora" guardará un log de eventos
realizados por un usuarios sobre un crud de datos.

Con simples QuerySet's escribimos la data necesaria para crear
los logs de las acciones del user.

## Versiones
```
Django==1.8.8
Python==2.7
```

## Tip

La base de datos es sqlite3, al
migrar se creara, así como
creara la tabla y campos descritos
en el modelo.

## Comandos usados en secuencia para probar el proyecto

$ python manage.py makemigrations registro

$ python manage.py migrate

$ python manage.py createsuperuser

$ python manage.py migrate

$ python manage.py runserver
