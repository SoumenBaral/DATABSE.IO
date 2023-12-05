# SQL Downloading process
Installing mysql in ubantu comment : 
1. sudo apt update 
2. sudo apt install mysql-server
3. sudo systemctl status mysql.service
4.  sudo mysql_secure_installation
5.  sudo mysql -u root -p
6.  sudo snap install mysql-workbench-community
7.  sudo mysql
8.  ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';
7.  @17060Sb


# Environment SetUp in Python for Linux and Activate venv :

You need to install python3-venv:
-------------------------------------
--> sudo apt install python3-venv

Then:
1. python3 -m venv vvv
2. virtualenv Project_name
3. source Project_name/bin/activate
4. pip install pymysql


# MysQl pakage install commend :

 --> pip install mysql-connector-python

# Get the version file 

--> pip freeze > requirement.txt






# Start Project in django final in global: 
-------------------------------------------
1. sudo apt install python3-django
2.  django-admin --version 
3. django-admin startproject myproject
4. cd myproject
5. python3 manage.py migrate
6. python3 manage.py createsuperuser
7. python3 manage.py runserver

# Crispy Form : 
---------------------------------------------------------
We already install it so we don't need to install it anymore :
via: pip install crispy-bootstrap5

Add This in Sattings.py

apps = (
    ...
    "crispy_forms",<br>
    "crispy_bootstrap5",
    ...
)

CRISPY_ALLOWED_TEMPLATE_PACKS = "bootstrap5"

CRISPY_TEMPLATE_PACK = "bootstrap5"




