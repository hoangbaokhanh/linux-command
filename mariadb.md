## Login
mysql -u root -p

## Create database
CREATE DATABASE **dbname** DEFAULT CHARACTER SET utf8 COLLATE utf8_unicode_ci;

## grant permission
GRANT ALL ON **dbname**.* TO '**user**'@'localhost' IDENTIFIED BY '**password**';
FLUSH PRIVILEGES;

## create user
CREATE USER foo IDENTIFIED BY 'password';

## select db
use dbnamel

## show db
show databases;

## show tables
show tables;
