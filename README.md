##Para crear un entorno virtual, utiliza: ##
python -m virtualenv web   (web en este caso).


Después de crear el entorno, actívalo según tu sistema operativo:
web\Scripts\activate  (web en este caso)


creamos la carpeta src 
mkdir src
cd src para navegar
 django-admin startproject project

correr la app
cd project (llamda asi en este caso)

python manage.py runserver 

SI SALE ESTE ERROR: 
You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.

Debemos ejecutar
python manage.py migrate

Configurar el administrador 
http://127.0.0.1:8000/admin/login/?next=/admin/

Crear Super user
python manage.py createsuperuser
crear usuario y contraseña para tener acceso