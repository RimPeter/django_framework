.venv\Scripts\Activate.ps1 (open virtual environment)
py manage.py runserver (run site on local host)
py manage.py startapp posts (to create 'posts' directory. You have to run it in directory where 'manage.py' is.)
py manage.py migrate (applies all migrations from the built in models that Django provided; You have to run it in directory where 'manage.py' is.)
py manage.py makemigrations (Creates migrations for the 'posts' app)

