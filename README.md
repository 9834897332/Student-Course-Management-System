🎓 Student Course Management System

📝 Overview

The Student Course Management System is a comprehensive database application designed using Oracle SQL and PL/SQL to manage student information, course enrollments, grades, and department-related data. This system facilitates the efficient handling of academic records and offers insights into student performance and course statistics.

✨ Features

📚 Student Management: Track student details including personal info, courses enrolled, and grades.
🏫 Course and Department Management: Manage information related to courses, departments, and faculty.
🎓 Enrollment and Grades: Register students into courses, and manage grade assignments with automatic triggers.
🔍 Advanced Queries: Analyze data to extract key insights like course popularity, enrollment trends, and student performance.
⚙️ Automated Procedures: PL/SQL procedures and triggers ensure data consistency, grade calculation, and enrollment validations.
🛠 Technologies Used

🗄 Oracle SQL: For database design, query execution, and data management.
🔧 PL/SQL: For creating stored procedures, triggers, and automating processes.
💻 SQL Developer: As the primary IDE for executing SQL and PL/SQL scripts.
📊 Database Schema

The database consists of the following main tables:

👨‍🎓 Student: Stores student information.
📘 Course: Holds course details such as course name and credits.
🏢 Department: Stores department data and links to courses.
📝 Enrollment: Links students and courses, storing grades.
🔗 Entity-Relationship (ER) Diagram

The system is built upon an optimized ER diagram connecting students, courses, departments, and enrollments to ensure relational integrity and efficient data retrieval.

📜 SQL Scripts

⚒️ Table Creation
SQL scripts for creating the Student, Course, Department, and Enrollment tables.
📥 Data Insertion
Sample data insertion scripts to populate the database with realistic entries.
🔍 Queries
Real-world SQL queries for:
Retrieving students enrolled in specific courses or departments.
Finding students with a certain grade or performance level.
Tracking enrollment trends and course popularity.
🧑‍💻 Example Queries

📊 Find students enrolled in more than 3 courses.
📑 Retrieve students who have taken courses from multiple departments.
📉 List courses with no enrollments (unused courses).
🚀 Installation and Setup

🔧 Install Oracle SQL: Ensure you have Oracle SQL or SQL Developer installed.
📂 Clone the Repository: Clone the repository from GitHub.
bash
Copy code
git clone [https://github.com/yourusername/student-course-management.git](https://github.com/9834897332/Student-Course-Management-System.git)
⚙️ Run SQL Scripts: Use SQL Developer or any Oracle SQL client to run the table creation and data insertion scripts.
💡 How to Use

Modify the SQL scripts to match your requirements or extend the schema to fit your data model.
Execute queries in SQL Developer to retrieve and analyze student and course-related data.
🤝 Contribution

Feel free to submit issues, fork the repository, and make contributions. Pull requests are welcome!
