# Style Guides

1. [Django][1]
1. [Flask][2]


[1]: Django
# Django

1. Description:
Django is a framework created for web developers on a deadline. Its idea is to get a MVC environment created quickly and efficiently

1. Advantages:
    All included framework, with a built-in administration interface.
    By default it'll work with a SQLite system and a Postgresql database will be highly recommended for a production environment, but all databases are supported.

1. Drawbacks:
    Lots of modules and addons have been developped for Django, some are current, some not maintained anymore, Also, sometimes the existing third party functionlaities

1. Installation Process:

    1. In your virtual environment (venv), use pip to install Django

    1. To start a new project use the following command:

    `django-admin.py startproject --template=$TEMPLATE_URL --extension=py,md,html,env $PROJECT_NAME`

    where TEMPLATE_URL is a pre_made site you can re-use as template, and PROJECT_NAME will be the name of the work directory created by this command
    --template and --extension are optional parameters
    1. Modify the settings in PROJECT_NAME/settings.py  so that the key is generated properly, install the dependances using `pip install -r requirements.txt`
    1. do a database migration using `manage.py migrate`, then run it manually to check it works properly `manage.py runserver:0.0.0.0`


1. links
    - [The Django project home page](https://www.djangoproject.com/)
    - [The Django Documentation](https://docs.djangoproject.com)
    - [ The Django Official tutorial](https://docs.djangoproject.com/en/1.10/intro/) <- Note, this is for the 1.10 version (the latest at the day this document was writen)
    - Django packages list

[2]: Flask
# Flask

1. Description:

1. Advantages:

1. Drawbacks:

1. Installation Process:
