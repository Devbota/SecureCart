# SecureCart

To run program download zip file then access visual studio code or any relevant Integrated Development Environment.

superuser has already been created: 

username: dLucas

email: david@gmail.com

password: importantuser12

Can create another admin using: python manage.py createsuperuser

Ensure you have the python modules: sslserver, Django and pillow:

pip install pillow

pip install django-sslserver

pip install django


Apply migrations if you have to: 

python manage.py makemigrations shop

python manage.py migrate

To run program, inside the terminal type: 

python manage.py runsslserver (applies local ssl)

If doesn't work then try:

python manage.py runserver (runs without local ssl)



