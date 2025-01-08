# database_backup_and_recovery

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: LATIKA SATISH KARKERA

**INTERN ID**: CT08DS9741

**DOMAIN**: SQL

**BATCH DURATION**: DECEMBER 10TH 2024 TO JANUARY 10TH 2025

#DESCRIPTION:

In this project, the goal was to demonstrate the process of backing up and restoring a database in the event of failure. The project follows a set of instructions to illustrate how to back up a database and its contents and how to restore the database to a previous state if necessary. For this demonstration, the school database was used, which contains a students table with basic information about students.

Project Overview
The school database was created to store information about students, including their ID, name, age, and grade. The students table is designed with an AUTO_INCREMENT primary key for the student_id, ensuring that each student has a unique identifier. The table also includes columns for student_name, age, and grade. Sample data was inserted into this table, representing students with different grades and ages.

Instructions Followed
The task required performing two major actions:

Backing up the database: This involves creating a backup of the database to protect against data loss or failure.
Restoring the database: In case of failure or data loss, restoring the database allows the system to return to a previously backed-up state.
Both of these actions are critical for database management and ensuring data integrity. The process of backing up and restoring the database can be done through SQL queries and file management systems.

1. Creating the Database and Table
The first step was to create a database named school and a table called students. The students table contains four columns:

student_id: An INT column that serves as the primary key and is auto-incremented.
student_name: A VARCHAR column that holds the name of the student.
age: An INT column that stores the student's age.
grade: A VARCHAR column that contains the student's grade.
The table was created successfully, and sample data was inserted to represent a few students. This data was essential for demonstrating the backup and restore process. After creating the table and inserting the data, the command SELECT * FROM students; was used to display the contents of the table.

2. Backing Up the Database
To back up a MySQL database, the backup process typically involves exporting the database's schema and data into a file. This backup file serves as a copy of the database at a specific point in time, including all the tables and the data within them.

Creating a backup of the school database involves generating a file that contains all the necessary SQL statements to recreate the database structure and its data. This backup file can be securely stored and later used to restore the database in case of failure or data loss.

3. Restoring the Database
In the event of a failure or data loss, the database can be restored from the backup file. Restoring a database involves importing the contents of the backup file into the database system. This process essentially runs the SQL statements stored in the backup file to recreate the database structure and repopulate the tables with the original data.

Once the restoration process is complete, the database will be returned to its previous state, with all tables and data intact, ensuring that no information is lost. The restored data can be verified by querying the tables and confirming that all records are correctly restored.

4. Verifying the Restoration
After restoring the database, it is important to verify that the data has been successfully restored. The same query used earlier, SELECT * FROM students;, can be executed to check if the table now contains the same data as before the failure.

Execution of Instructions
Following the instructions, the process of backing up and restoring the database was carried out step-by-step. First, the school database and students table were created, followed by inserting sample data. A backup was then generated, and the process of restoring the database was demonstrated by importing the backup file.

The backup file was used to restore the database to its original state. After restoration, the data in the students table was verified, confirming that the backup and restore processes were successful.

Conclusion
This project effectively demonstrated the process of backing up and restoring a MySQL database. By creating a backup file and later restoring the database from it, we ensured that the data could be protected from potential loss. The steps followed in this project are critical for database management, as they help ensure data integrity and recovery in case of failure.

Through this demonstration, it became clear that regular backups are essential for maintaining a secure database system. The ability to restore a database from a backup ensures that data can be recovered quickly and efficiently, minimizing downtime and preventing data loss.

#OUTPUT:
![Screenshot 2025-01-08 221156](https://github.com/user-attachments/assets/4f79ca56-37c2-42ca-b8a5-c238b3df1823)
![Screenshot 2025-01-08 221410](https://github.com/user-attachments/assets/7bdc867d-be89-4380-ab7c-11aaf91fe5a5)
![Screenshot 2025-01-08 221533](https://github.com/user-attachments/assets/2e2403c4-06d8-4f43-870d-39b1c77333d3)
![Screenshot 2025-01-08 221752](https://github.com/user-attachments/assets/b7fbe82a-e01a-4301-b592-6b55d619c142)
![Screenshot 2025-01-08 221819](https://github.com/user-attachments/assets/140ab8fe-ade2-4fcb-8af5-262d73705480)
![Screenshot 2025-01-08 221937](https://github.com/user-attachments/assets/db6e93d5-c21c-43e2-95c3-1f3cedf2580c)
