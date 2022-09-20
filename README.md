# DjangoQueryingLab_PY_Starter

Tech Stack: Python, MySQL

# Learning Objective

The objective of this project is to get more comfortable using the Django ORM query methods to retrieve data from a MySQL database. Many of your future projects, including the capstone, will require you to use similar Django ORM queries that you will be introduced to here. Your proficiency will grow with each project.

# Tasks

1. Complete the required queries in the  view.py file
2. Print your query results to the terminal and attempt to match the provided “Expected Terminal Result” as shown in the comments under each function. (Also shown in the browser) 
3. Utilize the Django Debug Toolbar to view the actual SQL that is executed by your ORM queries. 
4. Use the web page’s navigation buttons to execute the corresponding functions 


# Queries(9)

Note Each task is defined in the views.py file found in the school_db module.

1. Find all students and print their first_name, last_name, and GPA to the terminal

2. Find all students who have a GPA greater than 3.0. 
    Order the data by highest GPAs first (descending).
    Print out each student's full name and gpa to the terminal

3. Find all instructors hired prior to 2010
    Order by hire date ascending
    Print out the instructor's full name and hire date to the terminal

4. Find all courses that belong to the instructor that has the primary key of 2
    Print the instructors name and courses that he belongs to in the terminal
    (Do not hard code his name in the print)

5. Get the count of students, courses, and instructors and print them in the terminal 

6. Create a new student in the database. Use your information!
    Print the new student's id, full name, year, and gpa to the terminal
    NOTE: every time you execute this function a duplicate student will be created with a different primary key number
    
7. Query the previously created student by the id and update the "gpa" to a new value
    Then query the students table to get that student by their id
    Print the new student's id, full name, and gpa to the terminal

8. Delete the student that you have created and updated
    Check your MySQL Workbench to confirm the student is no longer in the table!
    
9. Find all of the instructors that only belong to a single course
    Print out the instructors full name and number of courses to the console