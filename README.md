# Django
#### Python version 3.6.8 compatiable by mysql
#### pip is python's package manager comes default with python used to add additional packages
#### Installing django
- pip install django

#### to know whether django is installed or not
- django-admin   --version
(or)
- django.get_version()
## django PROJECT Creation
- django-admin startproject projectname
  - this creates a folder with projectname which contains a folder named projectname and manage.py file
    - that projectname folder has 5 files
    - init.py : importing packages and modules
    - asgi.py:
    - settings.py : all apps,database,static files informations
    - urls.py : mentions all urls in this file
    - wsgi.py :web server gateway interface (for server purpose)
  
  - manage.py: to run our project by
  python manage.py runserver  ->127.0.0.1:8000
## After running our project by manage.py we automatically get db.sqlite3 file 
## **if you want to change the port number then python manage.py runserver 8080 -> 127.0.0.1:8080**
# **App Creation**
- python manage.py startapp appname
        or
        
- django-admin startapp appname
- this creates a number of files in the appfolder
  - migrations.py : tables are in form of classes
  **migrations is interface to convert class to table jst an interface dont convert**
  **migrate is use to convert class to table**
  - init.py: packages
  - admin.py : registering the table which are in form of class by which we can view the db
  - apps.py:app related info
  - models.py:contains all classes 
  - tests.py:testing
  - views.py:All logics
  
