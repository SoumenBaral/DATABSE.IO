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
2. source vvv/bin/activate


# MysQl pakage install commend :

 --> pip install mysql-connector-python

# Get the version file 

--> pip freeze > requirement.txt

