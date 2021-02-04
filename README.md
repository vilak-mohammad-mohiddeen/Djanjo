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
  
