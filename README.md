                                           		 AlstraSoft EPay Enterprise v4.20 Documentation

==================================================
Server requirements for Etheurium Mining 
==================================================
1.) MySQL (version 3.23 or higher)
2.) MYSQL database
3.) PHP (version 4.2.3 or higher)
4.) Crontab
5.) SSL (optional)


====================================
Installation And Setup Instructions: visit [Installation Guide](https://moneyaccounts.com/)
====================================
1. Unpack all files to the desired folder (example: /enterprise) and upload them to server thru FTP.

2. Set permission 777 for the following files and directories:
/config.htm
/templates (and all directories and the files in this directory)

3. Create new database and execute database.sql using a MySQL Db manager such as PHPMyAdmin

4. Open config.htm and set the following variables:
$db_hostname - database hostname;
$db_username - database username;
$db_password - database password;
$db_database - database name;
$folder - name of folder (if you install it in main folder for your site please leave it blank)

5. Configure cron sheduler to run /cron/rcharge.php once per day

6. Open /admins/ in your browser and enter "admin" as the login and the default password.

7. For editing of the templates, please refer to templates.txt file

Please visit [Guide](https://moneyaccounts.com/) to install the software properly
 
=====================
Running The Software:
=====================
Admin Login: [Login](https://moneyaccounts.com/) Default username: admin, password: admin
Main Page: [Main](https://moneyaccounts.com/)


