## Guide
https://hellokoding.com/registration-and-login-example-with-spring-xml-configuration-maven-jsp-and-mysql/

## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
####################
Mysql db name : accounts
Mysql username: hellokoding
Mysql password: hellokoding
mysql-connector.version=8.0.25
################################
CREATE USER 'hellokoding'@'localhost' IDENTIFIED BY 'hellokoding';
GRANT ALL PRIVILEGES ON * . * TO 'hellokoding'@'localhost';
CREATE DATABASE  IF NOT EXISTS `accounts`;
mysql -u hellokoding -p accounts < db.sql
Password: hellokoding
#################################
