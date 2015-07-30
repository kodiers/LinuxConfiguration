********* Linux Server Configuration ********

Server IP: 52.25.246.71
Server PORT: 2200
Server USER: grader

User grader have rights to sudo. 
Remote root login denied.

———————SSH———————

To get access to server via ssh enter:
ssh grader@52.25.246.71 -i [PATH_TO _PRIVATE_KEY] -p 2200

———————HTTP———————

Application ItemCatalog is available at http://52.25.246.71

———————SOFTWARE INSTALLED———————

###System software:###
Git

Apache 2.4.7 with mod_wsgi
Created default virtual host (config file: /etc/apache2/sites-available/ItemCatalog.conf) for servicing ItemCatalog software.

PostgreSQL 9.3
Created database “catalog” and user “catalog” as owner of this database.
Denied all external connection to database.

###Python modules:###
1. Flask 0.10.1
2. sqlalchemy 1.0.8
3. oauth2client 1.4.12
4. httplib2 0.9
5. Flask-SeaSurf 0.2.0
6. psycopg2 2.6.1

###Other###
ItemCatalog software
Installed in /var/www/ItemCatalog/ItemCatalog.