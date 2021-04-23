# Quiz-Management-System
• Windows Application in Java Netbeans • An executable window application which helps Teachers to take Quiz, manage the scores of students. • We can Add, Modify, and Delete the questions of the quiz. • During quiz we can see the Realtime score of our exam.

README :

1. First we have to create a database named qems and tables named student and question having following columns:

Question:

| Field  | Type         | Null | Key | Default | Extra |
+--------+--------------+------+-----+---------+-------+
| id     | varchar(10)  | NO   | PRI | NULL    |       |
| name   | varchar(500) | YES  |     | NULL    |       |
| opt1   | varchar(500) | YES  |     | NULL    |       |
| opt2   | varchar(500) | YES  |     | NULL    |       |
| opt3   | varchar(500) | YES  |     | NULL    |       |
| opt4   | varchar(500) | YES  |     | NULL    |       |
| answer | varchar(500) | YES  |     | NULL    |       |
+--------+--------------+------+-----+---------+-------+
7 rows in set (0.05 sec)

Student :

+----------------------+--------------+------+-----+---------+-------+
| Field                | Type         | Null | Key | Default | Extra |
+----------------------+--------------+------+-----+---------+-------+
| rollNo               | varchar(10)  | NO   | PRI | NULL    |       |
| name                 | varchar(100) | YES  |     | NULL    |       |
| fatherName           | varchar(100) | YES  |     | NULL    |       |
| motherName           | varchar(100) | YES  |     | NULL    |       |
| gender               | varchar(50)  | YES  |     | NULL    |       |
| contactNo            | varchar(10)  | YES  |     | NULL    |       |
| email                | varchar(100) | YES  |     | NULL    |       |
| tenthUniversityName  | varchar(200) | YES  |     | NULL    |       |
| tenthPercentage      | varchar(10)  | YES  |     | NULL    |       |
| tenthPassoutYear     | varchar(5)   | YES  |     | NULL    |       |
| twelveUniversityName | varchar(200) | YES  |     | NULL    |       |
| twelvePercentage     | varchar(10)  | YES  |     | NULL    |       |
| twelvePassoutYear    | varchar(5)   | YES  |     | NULL    |       |
| address              | varchar(500) | YES  |     | NULL    |       |
| marks                | int          | YES  |     | NULL    |       |
+----------------------+--------------+------+-----+---------+-------+
15 rows in set (0.01 sec)


2. We also have to change the address of mysql database , username and password in connection provider file. 

