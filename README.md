Learning Deployment with Render (free services)

Creating Table Commands:

$ flask db init
# => ...
$ flask db revision --autogenerate -m'create table birds'
# => ...
$ flask db upgrade
# => ...
$ python seed.py
# => ...

**Note: If <Error: No such command 'db' > encountered with flask db init need to pip install module/package name. Example for this application is <pip install psycopg2-binary>**

PYTHON_VERSION is 3.8.13
DATABASE_URI is <postgresql>