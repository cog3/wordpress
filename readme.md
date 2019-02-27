Christian Gomez

###### **HOW TO CONNECT TO WORDPRESS VIA PHPStorm**

1) Install PHP Storm and the latest version on PHP

Download PHP Storm: https://www.jetbrains.com/phpstorm/download/
**Disclaimer**
   You must have a license to use PHP Storm. You can receive a student license through your NJIT email. 
    
Download PHP: https://secure.php.net/downloads.php
**Disclaimer**
    It is recommended to Extract your /php folder into your C:\ drive. Always remember where
    you extracted this folder. 


2) Install MySQL

Link: https://dev.mysql.com/downloads/installer/

###### **MySQL Set Up**
1) Select _Standalone MySQL Server/Classic MySQL Replication_
2) Config Type = Development Computer
   TCP/IP Should be Checked
   Port = 3306 or 80
3) USE LEGACY AUTHORIZATION METHOD 
    ALWAYS REMEMBER YOUR MYSQL PASSWORD
    4) Finalize Setup & Execute Configurations

###### **Create Web Server Database**
1) Create New PHP Empty Project in PHPStorm
2) When in New Project, on the top right corner of PhpStorm click "Add Configuration"....
3) You will be taken to this screen, you are to drop down the menu on the left and select PHP Built-In Web Server
	- When Setting this up, the document root is the directory of the current project you are in

###### **wp-config-sample.php ----> wp-config.php**
	Take wp-config-sample.php and copy that into a new .php file names wp-config.php.
	Read the Documentation... then follow instructions
	DB_NAME = 'wordpress'
	DB_USER = 'root'
	DB_PASSWORD = 'password'
		DISCLAIMER: IT DEPENDS ON WHAT USERNAME/PASSWORD YOU USED FOR YOUR MYSQL LOGIN. WE RECOMMEND KEEPING IT SIMPLE WITH JUST......
		username = root
		password  = password
	DB_HOST = 'localhost' or '127.0.0.1'