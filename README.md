DJANGO REST FRAMEWORK (Paso a paso)

DRF: https://www.django-rest-framework.org/
YouTube: https://www.youtube.com/watch?v=GE0Q8YNKNgs

Crear carpeta con el nombre del proyecto

CREAR ENTORNO VIRTUAL (Virtual env)
F1 -> Crear nueva terminal
Nota: La terminal debe encontrarse en la ubicación de la carpeta creada

pip install virtualenv
python -m virtualenv venv (crea carpeta del entorno virtual)
.\venv\Scripts\activate

Python: Seleccionar intérprete (Seleccionar intérprete de la carpeta creada venv)

pip install django (instalar Django)
pip install djangorestframework
django-admin startproject [nombre] . (crear proyecto)
python manage.py runserver (ejecuta servidor)
python manage.py startapp [nombre] (crear aplicación)

settings.py -> INSTALLED_APPS -> rest_framework (módulo rest framework, es externo a Django)
También se debe agregar las aplicaciones

MODELO DE PROYECTO
models.py (Crear la estructura de las tablas)
python manage.py makemigrations (Realiza las migraciones)
python manage.py migrate (Crea todas las tablas por defecto de Django más lo que creamos)

CREAR LA API REST (Serializers)
Crear archivo serializers.py
Crear archivo api.py
Crear archivo urls.py

Ir al archivo del proyecto -> urls.py
Agregar en el urlpatterns el archivo urls creado

Extensiones -> Thunder Client (VS Code, para probar patch, delete)
