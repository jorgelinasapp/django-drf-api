Django DRF API

API REST desarrollada con Django y Django REST Framework utilizando SQLite como base de datos.

Descripción

Este proyecto fue realizado como trabajo práctico para el módulo de Programación II de la Tecnicatura Superior en Desarrollo Web y Aplicaciones Móviles, bajo la cátedra de la profesora Rojas Córsico, Ivana Soledad.

La API permite gestionar usuarios y roles mediante endpoints REST, implementando modelos, serializadores y vistas basadas en APIView.

Tecnologías utilizadas
Python 3
Django
Django REST Framework
SQLite

Instalación y ejecución
Clonar el repositorio:
git clone https://github.com/jorgelinasapp/django-drf-api.git
cd django-drf-api
Crear entorno virtual:
python -m venv venv
Activar entorno:

Windows:venv\Scripts\activate

Linux-Mac:source venv/bin/activate

Instalar dependencias: pip install -r requirements.txt
Aplicar migraciones:python manage.py migrate
Ejecutar servidor:python manage.py runserver
Endpoints
GET /api/users/ → listar usuarios
POST /api/users/ → crear usuario
GET /api/roles/ → listar roles
POST /api/roles/ → crear rol
Notas a tener en cuenta:
Se utiliza SQLite como base de datos por defecto.
El entorno virtual (venv) y la base de datos no se incluyen en el repositorio.
Las dependencias se gestionan mediante requirements.txt.
Autora: https://github.com/jorgelinasapp
