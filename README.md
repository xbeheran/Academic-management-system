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
