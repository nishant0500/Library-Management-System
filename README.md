# Library-Management-System
Library Management System project using Netbeans (java).

# System Configuration
 1. NetbeansIDE --version.8 or above.
 2. MySql DataBase (Mysqlworkbench)

# Project Description 
  Library Management System ,this project is completely based on Java and Jswing package.
  The various modules of the projects are described below :blush: :
 - [Login](https://github.com/nishant0500/Library-Management-System/blob/master/src/login.java)
    - It allows the Admin to login the application (You can set your own username and password ).
 - [Home](https://github.com/nishant0500/Library-Management-System/blob/master/src/home.java)
    - Once you are logged in then this module will pop up . It contains various navigtion buttons through which you can switch different module.
 - [New Student](https://github.com/nishant0500/Library-Management-System/blob/master/src/NewStudent.java)
    - This module will add or remove student from the database.(Note:It will only remove student when book is returned.you can remove student by only             providing studentId)
 - [New Book](https://github.com/nishant0500/Library-Management-System/blob/master/src/NewBook.java)
    - This module will add new books in the database.
 - [Issue Book](https://github.com/nishant0500/Library-Management-System/blob/master/src/issueBook.java)
    - This module will handle operation of issuing book and updates values in database.
 - [Return Book](https://github.com/nishant0500/Library-Management-System/blob/master/src/returnBook.java)
    - This module can search the issue details by getting studentId and BookId and handle return operations.
 - [Statistics](https://github.com/nishant0500/Library-Management-System/blob/master/src/statistics.java)
    - Here comes an intresting module where you can track the records of issued book and returned book.
 - [Logout]()
    - It's simply transfer the controls to login page where you can exit the application.
    
 # Demo
 - You need to Add this add this jar files : [Additional files](https://github.com/nishant0500/Library-Management-System/tree/master/Additional%20JAR%20files) Here you have jCalender.jar which is usally not available in NetbeansIDE so you need to add in plaette
and rs2xml.jar which provides DbUtils services and xml services you need to add it into yours libraries.
- You can watch the live Demo of working Project [HERE](https://drive.google.com/drive/folders/1CMQ8Fu0mtTuFj6HLly17NenE_4jxKatl) :+1:
