This is a project that I completed as a part of the Forge program (https://joinforge.co/launch-ds) that I eventually taught. It was completed over the course of one week along with 3 other data science trainees. 

The Project Brief was as follows: 

**Learning Management System Data Model:** 

You are a data science team working for an e-learning platform that offers various courses on different topics. You need to design a database schema that can store and track the information of the courses, students, and grades. You also need to ensure that the schema can calculate grades based on the student's performance on the assignments and exams. Four required tables are:
- Courses: This table stores the information of each course, such as its name, code, description, instructor, syllabus, etc.
- Students: This table stores the information of each student, such as their name, ID, email, profile, etc.
- Assignments: This table stores the information of each assignment, such as assignment ID, course ID, assignment title, description, due date, weight, etc.
- Grades: This table stores the information of each grade transaction, such as the enrollment ID, assignment ID, score, feedback, date, etc.

Deliverables:
1. Two databases - one MySQL, one MongoDB- that you have spun up locally and populated with your data according to your specified architecture. 
2. A polished, 10-12 minute slide deck presentation detailing the data you created or obtained, the architectural decisions you made for each of the two databases, and which database architecture you feel best suits your topic. Make sure to talk about the performance of queries for each database in the slide deck! This is a technical presentation to be shared with your CTO or technical project manager. Don’t hold back on the jargon, but still explain concepts in-depth and avoid code screenshots.

You can find the data we fabricated, code, and slides in this GitHub repository. If you seek to replicate the project, make sure to change your database name and passwords accordingly. Also, you must run the code locally (e.g. VS Code). It will not work in Google Colab. I also recommend using MySQL Workbench and MongoDB Compass as friendly GUIs. 
