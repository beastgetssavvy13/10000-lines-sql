## The Pixelated Coder  :man_technologist:

> Contributor : Kavish Pandit 

<H2>SQL JOURNEY</H2>
============
## :busts_in_silhouette: Author
- [Kavish Pandit](https://github.com/beastgetsssavvy13)

_My journey of 10000 lines of sql commands using 3 databases_

### DATABASED INVOLVED 

_DataBases : School | Company | OnlineShop_

_Tables : School :? Students | teachers | subjects_

_Tables : Company :? Employess | Clients  | Projects_

_Tables : Onlineshop :? Items | Categories | Customers |Orders_


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
