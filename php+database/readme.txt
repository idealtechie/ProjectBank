Open Xampp
Start Apache and Mysql
======================================================

Type Following Commands in cmd: (for creating Database)
======================================================

cd\
cd xampp
cd mysql
cd bin
mysql.exe -u root
create database sample;
use sample;
create table student(sname varchar(20),regno INT,m1 INT,m2 INT);
After this minimize the cmd window.
=======================================================

Download this folder andPaste it into htdocs
Open Browser and enter localhost/(foldername) in address bar and press enter.
There you will find two files (1html+1php)
Open the Html file and Enter Details.
=======================================================

After inserting data in html file.
Open the cmd window which was minimized earlier
And then use select * from student in cmd to view the inserted value.
