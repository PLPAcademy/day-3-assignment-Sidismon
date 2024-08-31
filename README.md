[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vnsr1XuU)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15625320&assignment_repo_type=AssignmentRepo)
# Env_Set

# Environment Setup Assignment

#Dart & Flutter

1. What is the first step for installing Dart on a Windows machine?

A) Install Homebrew
B) Download the Dart SDK
C) Update your PATH
D) Run Dart Doctor
ANSWER: 
    B) Download the Dart SDK

2. Which command verifies the Dart installation on macOS?

A) dart --install
B) dart --check
C) dart --verify
D) dart --version
  ANSWER:
      D) dart --version

3. What is the next step after downloading and extracting the Flutter SDK on Linux?

A) Install Homebrew
B) Update your PATH
C) Run Flutter Doctor
D) Create a new Flutter project
  ANSWER:
      B) Update your PATH  

4. What command is used to run a newly created Flutter app?

A) flutter start
B) flutter build
C) flutter run
D) flutter init
AAMSWER:
      C) flutter run

#Python Installation

What is the first step to install Python on a Windows system?

A) Run the installer without any customization
B) Download Python from the official website
C) Open the terminal and type sudo apt install python
D) Install pip manually
  ANSWER:
       B) Download Python from the official website
       
Which option should you ensure is checked during Python installation on Windows?

A) Install with default settings
B) Install to a custom directory
C) Add Python to PATH
D) Install all available features
    ANSWER:
         C) Add Python to PATH
    
How do you verify Python installation on any system?

A) By running python --version
B) By restarting your computer
C) By opening the Python installer again
D) By checking the Programs and Features in Control Panel
    ANSWER:
         A) By running python --version
What command is used to install pip on macOS and Linux?

A) sudo install pip
B) pip install python
C) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
D) python --install pip
    ANSWER: 
        C) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
        
What is the purpose of a virtual environment in Python?

A) To keep your projects organized in one folder
B) To install Python in a different directory
C) To separate project dependencies and avoid conflicts
D) To enhance Python performance on your system
   ANSWER: 
        C) To separate project dependencies and avoid conflicts
#MySQL Installation

What is the first step to install MySQL on Windows?

A) Download MySQL Shell
B) Download MySQL Installer from the official website
C) Install MySQL Workbench
D) Set up a root password
   ANSWER:
        B) Download MySQL Installer from the official website
        
What setup type should you choose for a custom MySQL installation?
A) Developer Default
B) Server Only
C) Full
D) Custom
 ANSWER:
     C) Full
Which products should you select during the MySQL installation?

A) MySQL Server, MySQL Workbench, and MySQL Shell
B) Only MySQL Server
C) MySQL Server and MySQL Router
D) MySQL Workbench and MySQL Utilities
AMSWER:
     A) MySQL Server, MySQL Workbench, and MySQL Shell
What is the purpose of setting a root password during MySQL installation?

A) To create a user account for your MySQL server
B) To secure your MySQL installation with a super-secret password
C) To activate MySQL Workbench
D) To allow multiple users to access MySQL
 ANSWER:
       B) To secure your MySQL installation with a super-secret password
How do you begin managing your database after installing MySQL?
ANSWER:
     Step 1: Log in to MySQL Server
Open a terminal window and type the following command:
mysql -u root -p
Enter your MySQL root password when prompted.
Step 2: Create a User
Create a database user with limited privileges to manage the database:
CREATE USER 'dbuser'@'localhost' IDENTIFIED BY 'strong_password';
Step 3: Grant Privileges to the User
Grant the user necessary privileges to the database:
GRANT ALL PRIVILEGES ON *.* TO 'dbuser'@'localhost' WITH GRANT OPTION;
Step 4: Create a Database
Create a database for your application:
CREATE DATABASE my_database;
Step 5: Use the Database
Select the newly created database:
USE my_database;
Step 6: Create Tables and Insert Data
Create tables and insert data into your database using SQL commands.
Step 7: Monitor Database Performance
Use tools like
SHOW STATUS
and
SHOW PROCESSLIST
to monitor database performance and identify bottlenecks.
Step 8: Configure Backup and Recovery
Configure regular backups to protect your database from data loss. Set up a recovery plan to restore data in case of a failure.
Step 9: Optimize Database Performance
Optimize database performance by creating indexes, tuning queries, and considering database fragmentation.
Step 10: Manage Security
Ensure database security by implementing strong passwords, user authentication, and access control mechanisms.

A) Start by installing additional plugins
B) Launch MySQL Workbench and connect to your MySQL Server
C) Run mysqladmin start in the terminal
D) Restart your computer to activate MySQL
