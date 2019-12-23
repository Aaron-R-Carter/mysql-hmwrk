CREATE TABLE employee(
first_name varchar(30),
last_name varchar(30),
);

CREATE TABLE department(
department_name varchar(30),
department_id INTEGER(4) auto_increment not null,
primary key (department_id) 
);

CREATE TABLE role(
title varchar(30),
salary decimal
);

