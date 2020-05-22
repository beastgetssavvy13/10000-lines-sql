## The Pixelated Coder  :man_technologist:
:pencil: SQL JOURNEY
============

## :busts_in_silhouette: Author

- [Kavish Pandit](https://github.com/beastgetsssavvy13)

_My journey of 10000 lines of sql commands using 3 databases_

## :tada: ALL SQL COMMANDS USED

- [Sql Link](https://github.com/beastgetssavvy13/10000-lines-sql-journey/blob/master/SQL.txt)

### DATABASED INVOLVED 
| DataBases | Name  |  School  | Company |  OnlineShop ||
| ------- | ----------- | ----------- | ----------- |----------- |----|
| Tables | School | Students| Teachers| Subjects |
| Tables | Company| Employess|  Clients |  Projects |
| Tables | Onlineshop| Items| Categories| Customers| Orders |

### Basic Snapshotting
mysql> CREATE USER 'admin' IDENTIFIED BY 'password1234';

Query OK, 0 rows affected (0.02 sec)
//CHANGE PASSWORD

mysql> ALTER USER 'admin' IDENTIFIED BY 'php1234';
Query OK, 0 rows affected (0.01 sec)

//GRANT ALL PRIVELLEGES TO ALL DB (*) ALL TABLES (*) TO THE USER 'ADMIN' WITH USER CAN SET PRIVELLEGES AND NEW USER

mysql> GRANT ALL ON *.* TO 'admin' WITH GRANT OPTION;
Query OK, 0 rows affected (0.02 sec)
//PRIVILEGES TO TAKE PLACE

mysql> FLUSH PRIVILEGES;

//EXIT TO LOG IN TO ADMIN

### SCHOOL

<img src="https://github.com/beastgetssavvy13/10000-lines-sql-journey/blob/master/1.JPG"/>

### COMPANY

<img src="https://github.com/beastgetssavvy13/10000-lines-sql-journey/blob/master/2.JPG"/>

### ONLINESHOP

<img src="https://github.com/beastgetssavvy13/10000-lines-sql-journey/blob/master/3.JPG"/>


## Description: 
Created an application using React Hooks and Express Js Server. Feel free to reach out if any issues :raised_hands:
