---

# Finals Lab Task 3-1
This portfolio demonstrates the application of MySQL SELECT Clauses to query and retrieve data from a relational database. The task builds upon a predefined database structure and focuses on extracting meaningful insights using various SELECT statement features.

---

## STEP BY STEP PROCESS

### STEP 1. Launch MySQL Workbench or phpMyAdmin and start XAMPP to activate MySQL.

### STEP 2. Open MySQL Workbench or phpMyAdmin and download/import the onlineCourse.sql file to initialize the tables and data.

### STEP 3. Create and select the working database:
- Create a database named online_courseDB
- Use the database created

### STEP 4. Import the provided initial SQL structure (onlineCourse.sql) into the online_courseDB to load the necessary tables and sample data.

### STEP 5. For each of the following tasks, write and execute the appropriate SELECT query to extract the required information:

- #### Task 1 – Retrieve all courses where students enrolled is less than the enrollment limit
  - Use SELECT with a WHERE clause to find courses where `students_enrolled` is less than `enrollment_limit`.

- #### Task 2 – Group courses by category and calculate the total number of students enrolled for each category
  - Use GROUP BY with an aggregate function like SUM(`students_enrolled`) to summarize student enrollment by course category.

- #### Task 3 – Retrieve courses that are fully enrolled
  - Use SELECT with a WHERE condition to filter courses where `students_enrolled` equals `enrollment_limit`.
    
- #### Task 4 – Calculate the total number of students enrolled across all courses
  - Use an aggregate function like SUM(`students_enrolled`) to compute the total enrolled students from all courses.

- #### Task 5 – Sort courses by students enrolled in ascending order
  - Use ORDER BY `students_enrolled` to arrange the courses based on the number of enrolled students.

---

## Query Statements (Screenshots)
- ### Task 1
![screenshot](images/FLT3-1(T1).png)
- ### Task 2
![screenshot](images/FLT3-1(T2).png)
- ### Task 3
![screenshot](images/FLT3-1(T3).png)
- ### Task 4
![screenshot](images/FLT3-1(T4).png)
- ### Task 5
![screenshot](images/FLT3-1(T5).png)

---

## Table Structures (Screenshots)
- ### Table 1
![screenshot](images/FLT3-1(tbl1).png)
- ### Table 2
![screenshot](images/FLT3-1(tbl2).png)
- ### Table 3
![screenshot](images/FLT3-1(tbl3).png)
- ### Table 4
![screenshot](images/FLT3-1(tbl4).png)
- ### Table 5
![screenshot](images/FLT3-1(tbl5).png)

---

## SQL Copy (File)
> 📂 

---



