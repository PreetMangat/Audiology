# Audiology
Music Player written in Javascript, HTML, CSS and PHP, using a MySQL database to store songs , users and playlists.

![register-screen](https://i.imgur.com/UruYbo4.png)
![home-screen](https://i.imgur.com/bwB7XWU.png)
![album-screen](https://i.imgur.com/3lrAnPu.png)

## Installation

##### Dependencies
-XAMPP 7.4.2 (can be downloaded here: https://www.apachefriends.org/index.html  
-XAMPP is a free and open-source cross-platform web server solution stack package developed by Apache, consisting mainly of the Apache HTTP Server, MySQL database, and interpreters for scripts written in PHP.

##### Steps

1) Clone repo into the htdocs folder, which is located inside the XAMPP folder.
2) Run xampp-control.exe and start Apache and MySQL
3) Go to Localhost/phpmyadmin, create a new database named 'audiology'
4) click on the audiology database, and select import
5) import the database file located at \xampp\htdocs\Audiology\Build_Mysql_DB , and press run
6) Once the DB is created, navigate to localhost/audiology/register.php to begin the app
