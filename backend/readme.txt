Please run the following command to create the table before run the app.js

1. create database employees_db

2. CREATE TABLE IF NOT EXISTS `EMPLOYEES` (
   emp_id int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
   emp_name varchar(255) NOT NULL,
   emp_contact varchar(10),
   emp_add varchar(255) DEFAULT false
   ) ENGINE=InnoDB DEFAULT CHARSET=utf8;