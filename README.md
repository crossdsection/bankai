# bankai
This is an experimentation to hone my skills

Setting Up on CentOs
----------------------------

Mysql Installation
===========

sudo yum update

wget http://repo.mysql.com/mysql-community-release-el7-5.noarch.rpm
sudo rpm -ivh mysql-community-release-el7-5.noarch.rpm
sudo yum update
sudo yum install mysql-server
sudo systemctl start mysqld
sudo mysql_secure_installation

Django Installation
===========
sudo yum install python-pip
sudo pip install django
