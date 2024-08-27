# Academic-management-system
The Academic Management System is designed to manage student information, course details, and student enrollments in courses using SQL.
1. Database Creation
The project begins by creating three essential tables:

StudentInfo: Contains information about students, including their ID, name, date of birth, contact details, and address.
CoursesInfo: Stores course details, including the course ID, course name, and the instructor's name.
EnrollmentInfo: Manages enrollment information, linking students to courses and tracking their enrollment status. This table references the StudentInfo and CoursesInfo tables through foreign keys.
2. Data Insertion
Sample data is inserted into each of the three tables to simulate real-world scenarios. This data is used to test the queries and ensure that the system functions correctly.

3. Queries for Retrieving Information
Several SQL queries have been developed to retrieve specific information from the database:

Student Information: Retrieve student details, including contact information and enrollment status.
Course Enrollment: Retrieve the list of courses in which a specific student is enrolled.
Course Information: Retrieve details about courses and their instructors.
Specific Course Queries: Retrieve information for specific or multiple courses.
4. Reporting and Analytics
Advanced SQL queries are used to generate reports and perform analytics on the data:

Student Enrollment by Course: Retrieve the number of students enrolled in each course.
Students in Specific Courses: List students enrolled in a specific course.
Instructor Enrollment Count: Retrieve the count of students enrolled for each instructor.
Multiple Course Enrollments: Identify students enrolled in multiple courses.
Courses with Most Enrollments: Retrieve a list of courses with the highest number of enrolled students.
The Student Database Management System is a PostgreSQL-based project designed to store, retrieve, and manage student information efficiently. The project includes tasks such as database setup, data entry, information retrieval, updates, and advanced SQL queries to analyze and manipulate the data. The system handles essential student details like names, departments, contact information, academic performance, and more.

Project Structure
1. Database Setup
Create the Database:
A database named student_database is created to store the student information.
Create the student_table:
The table student_table is created with columns for Student_id, Stu_name, Department, email_id, Phone_no, Address, Date_of_birth, Gender, Major, GPA, and Grade.
The Grade column is restricted to values 'A', 'B', 'C', 'D', and 'F' using a CHECK constraint.
2. Data Entry
Insert Sample Records:
Ten sample student records are inserted into the student_table. These records include various student details such as name, department, GPA, grade, and more.
3. Student Information Retrieval
Retrieve All Students Sorted by Grade:
A query is developed to retrieve all student information, sorted in descending order by their grade.
4. Query for Male Students
Retrieve Information About All Male Students:
This query retrieves all the records of male students from the student_table.
5. Query for Students with GPA Less Than 5.0
Fetch Details of Students with Low GPA:
A query is created to retrieve the details of students with a GPA less than 5.0.
6. Update Student Email and Grade
Update Email and Grade for a Specific Student:
This update statement allows modification of the email and grade of a student with a specified Student_id.
7. Query for Students with Grade "B"
Retrieve Names and Ages of Students with Grade "B":
A query is developed to retrieve the names and ages of students who have a grade of "B".
8. Grouping and Calculation
Group by Department and Gender, Calculate Average GPA:
This query groups the students by department and gender, then calculates the average GPA for each group.
9. Table Renaming
Rename student_table to student_info:
The table student_table is renamed to student_info for clarity and consistency.
10. Retrieve Student with Highest GPA
Retrieve the Name of the Student with the Highest GPA:
A query is developed to retrieve the name of the student with the highest GPA from the student_info table.
The Event Management System is a PostgreSQL-based application designed to help users create, manage, and track events, attendees, and registrations efficiently. The project includes the creation of a database and tables, data insertion, management of event details, attendee tracking, and development of queries to retrieve and analyze event information.

Project Structure
1. Database Creation
Create the Database:
A database named EventsManagement is created to store the information related to events, attendees, and registrations.
Create Tables:
Events Table: Stores event details including Event_Id, Event_Name, Event_Date, Event_Location, and Event_Description.
Attendees Table: Stores attendee details including Attendee_Id, Attendee_Name, Attendee_Phone, Attendee_Email, and Attendee_City.
Registrations Table: Stores registration details including Registration_id, Event_Id, Attendee_Id, Registration_Date, and Registration_Amount. This table references the Event_Id from the Events table and the Attendee_Id from the Attendees table as foreign keys.
2. Data Creation
Insert Sample Data:
Sample data is inserted into the Events, Attendees, and Registrations tables to simulate real-world event management scenarios.
3. Manage Event Details
Insert a New Event:

Allows the insertion of a new event into the Events table.
Update an Event's Information:

Allows updating the details of an existing event in the Events table.
Delete an Event:

Allows deletion of an event from the Events table.
4. Manage Attendees & Handle Event Registrations
Insert a New Attendee:
Allows the insertion of a new attendee into the Attendees table.
Register an Attendee for an Event:
Allows the registration of an attendee for a specific event by inserting data into the Registrations table.
5. Develop Queries
Retrieve Event Information:

Retrieves all the information about the events from the Events table.
Generate Attendee List for a Specific Event:

Retrieves the list of attendees registered for a specific event.
Calculate Event Attendance Statistics:

Retrieves the total number of attendees and the total revenue generated for each event.
This project focuses on performing OLAP (Online Analytical Processing) operations on sales data using PostgreSQL. The goal is to analyze sales data through various dimensions, aggregations, and filters to gain deeper insights into the performance across different regions, products, and time periods.

Project Structure
1. Database Creation
Database:

A database named sales_analysis is created to store sales data.
Table:

A table named sales_sample is created with the following columns:
Product_Id (Integer): Identifies the product.
Region (varchar(50)): Represents the region of the sale (e.g., East, West, North, South).
Date (Date): The date on which the sale occurred.
Sales_Amount (numeric): The amount of sales.
2. Data Creation
Sample Data:
Ten sample records representing sales data are inserted into the sales_sample table. These records simulate real-world sales transactions across different regions and products.
