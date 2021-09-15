# DjangoCRUD-PostgreSQL

## Environment :
```
1. Python
2. Django
3. pgAdmin4 / PHPmyadmin
4. Visual Studio Code
```

## Start Server:
```
1. Dont foget to import DB :
mysql_DBver.sql for MySQL
pgsql_DBverSchemas.sql for PostgreSQL
Import on NetCRUD > settings.py > Line 83 (adjust it with your database credentials).

2. Run Server :
$ python manage.py runserver
```

## for MySql :
```
Please change on NetCRUD > settings.py > Line 83 to :
'django.db.backends.mysql'
```

## for PostgreSQL :
```
Please change on NetCRUD > settings.py > Line 83 to :
'django.db.backends.postgresql'

Import Schemas :
1. Goes to pgAdmin4
2. Select Server
3. Create Database
4. Goes to query tools, open pgsql_DBverSchemas.sql.
5. Copy the contents and paste in the query tool.
6. Click play button to create a schemas.

you are free to choose import database full or database scheme.
```

## Access on:
```
localhost:8000
```

