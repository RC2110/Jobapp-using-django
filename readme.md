 django-admin startproject myweb .
 
 python manage.py startapp web_application


python manage.py runserver

python manage.py makemigrations

python manage.py migrate

if any change in the table created(backend), 
you will need to makemigrations and migrate 
once again.

1.within webapp go to views and define functions to view the webpage using render.
2. create a new directory in webapp and name it template.
3. create the html files here so that it can be routed to views.
4. create a urls.py file to configure url patterns. call the views.function here and give it a name.
5. Now go to the project folder->urls and add the web application url using path and include.


Django expects '.' before the module name for the once in the same directory.

