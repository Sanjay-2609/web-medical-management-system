# web-medical-management-system
Problem Statement
Currently, SUST Medical Centre uses manual (primitive) Management System for maintaining the patient demography and distributing medicine to the patient. In the existing system, doctors and other employees have to spend a lot of time to provide services to the patient because a lot of papers are used to record information. Here, all the tasks (e.g., prescribing patient, delivering medicine, maintaining medicine stock, retrieving records etc.) are tremendously manual and paper dependent. Therefore, an automated online management system needs to be developed.

Project Overview
This system will provide a graphical user interface to maintain the whole system, including prescribing patient, delivering medicine, maintaining medicine stock etc. Moreover, the new system will be accessible from terminals within the Medical Center and also through the internet from computers outside the Medical Center. Besides, the patients (both student and staff) can view their prescription through internet from anywhere.

Users
General User (Patient): Student, Staff.

Administrative User: Doctor, Pharmacist, Store Officer, Medicine Distributor.

Major Functions
The main facilities will be available in this project are:-

Total existing management system will be computerized.
Maintaining patients diagnosis details, advised tests to be done.
Maintaining patient’s prescription, medicine, medication instructions, precautions and diet advice details.
Providing and maintaining all records of stock medicine through two subcategory central-store and sub-store.
The system will keep all tracks of newly purchased medicine and also monitoring their flow.
Billing report for the patient who are employee and Report generation.
The system will able to provide a proposed list of medicine that should be purchased in upcoming month.
If user forgets his/her password then it can be retrieved by hint question.
System Interfaces
Client on Internet: Web Browser, Operating System (any).
Client on Intranet: Client Software, Web Browser, Operating System (any).
Web Server: Apache Tomcat, Operating System (any).
DataBase: MySQL.
User Interface
User interfaces for all users are graphical user interfaces (GUI). These GUI could be both web based and desktop based which is connect to the medical central terminal. The user interfaces are pretty simple and straight-forward.

Communication Interface
Client on Internet will be using HTTP/HTTPS Protocol.
Client on intranet will be using TCP/IP protocol.
Requirements & Installation
Requirements:

jdk-6u1-windows-i586-p
netbeans-6.9.1-ml-windows
MySql Database
mysql-5.1.39-win32_2
mysql-connector-odbc-5.1.6-win32
mysql-gui-tools-5.0-r17-win32
mysql-connector-java-5.1.6-bin.jar
Apache Tomcat 6.0.26 (integrated with netbaens)
Firefox (3.6.3 or higher)
Installation:

Install JDK.
Install NetBeans IDE (Version 6.9.1).
We used MySQL database in this project. We have to install three components of MySQL. In our case root and admin are the username and password respectively for MySQL. (If you want to change the username & password then open database.java file from project\MedicalCentre\src\java\medicalcenter location and change username or password according to your MySQL database username and password).
Install Firefox web browser.
Open NetBeans IDE and import the MedicalCentre project as web project.
Add mysql-connector-java-5.1.6-bin.jar in Libraries if not added before.
