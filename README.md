# NairobiAcademy SQL Database Project

This project demonstrates the design and implementation of a relational database using PostgreSQL. 
The project involves:
- Creating the database schema
- Table relationships
- Inserting data
- Manipulating the data (UPDATE, DELETE)
- Querying the data
- Conditional Logic

### Project Structure
``` nairobiacademy.sql``` Contains all database queries
``` Readme.md``` Project documentation

### Database Design
#### 1. Schema
   ```
   CREATE SCHEMA IF NOT EXISTS nairobi_academy;
   SET search_path TO nairobi_academy;
   ```
#### 2. Tables
  ### Students
  Stores student information:
  - student_id (Primary Key)
  - first_name
  - last_name
  - gender
  - date_of_birth
  - class
  - city


  ### Subjects
  Contains subject details:
  - subject_id (Primary Key)
  - subject_name
  - department 
  - teacher_name
  - credits
 
  ### Exam_Results
  Links students to subjects and stores:
  - result_id (Primary Key)
  - student_id (Foreign Key)
  - subject_id (Foreign Key)
  - marks
  - exam_date
  - credit_hours

#### 3. Database Data:
- 10 Students
- 10 SUbjects
- 10 Exams Results
  
### Features implementend
  - Schema creation
  - Table Creation
  - Inserting sample data
  - Making updates on existing data
  - Deleting some records
  - Filtering data using conditions
  - Making range queries
  - Counting records
  - Classifying exam performance (Distinction, Merit, Pass, Fail)

### How to run the sql file
1. Open PostgreSQL, pgAdmin or CLI
2. Import or run the ``` nairobiacademy.sql``` file
3. Execute the queries

### Learning Outcome
- Relational databases and the design principles
- Use of primary and foreign Keys
- Writing SQL queries






