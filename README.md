# LMS

Coaching Center Management System
Prepared by: Badhon
1. Introduction
Running a coaching center involves a lot of daily paperwork: student admission, attendance, fee collection, exam results and teacher salaries. This document proposes a web-based Coaching Center Management System that handles all of this in one place.
2. Problem
• Student records kept in notebooks are slow to search and easy to lose.
• It is hard to keep an accurate account of who has paid fees and who still owes.
• Attendance and exam results are not reported to guardians, or are reported late.
• Coordinating teachers, batches and class routines takes extra effort.
3. Objectives
• Keep all coaching center data in one secure place.
• Make fee collection and accounting simple and transparent.
• Speed up communication with students and guardians.
• Reduce paperwork and save time.
4. Core Features
Admin Panel
• Add, edit and delete students, teachers and batches
• Dashboard showing total students, today's attendance, monthly income and pending fees
• Report generation and download
Student Management
• Admission form and student profile
• Student list by batch and subject
• Student progress history
Attendance
• Take daily attendance by batch
• Monthly attendance report
• SMS or notification to guardians when a student is absent
Fees and Accounts
• Set monthly fees and record payments
• List of pending fees with reminders
• Generate payment receipts
• Teacher salary records
Exams and Results
• Create exams and enter marks
• Results and merit list
• Student performance graph
Teacher Panel
• View own batches and class routine
• Enter attendance and marks
• Upload notices and study material
Student and Guardian Panel
• View own attendance, results and fee status
• View notices and routine
5. Users
User
What they can do
Admin
Manage everything and view reports
Teacher
Attendance, marks and notices
Student
View own information, results and routine
Guardian
View child's attendance, results and fees
6. Proposed Technology
• Frontend: HTML, CSS, JavaScript (or React)
• Backend: Node.js with Express (or Django / Laravel)
• Database: MongoDB or MySQL
• Version control: Git and GitHub
The stack can be changed to match whatever your project actually uses.
7. Database Tables (Summary)
• Students: name, phone, guardian phone, address, admission date, batch
• Teachers: name, phone, subject, salary
• Batches: batch name, subject, time, teacher
• Attendance: student, date, status (present/absent)
• Payments: student, month, amount, date
• Exams: exam name, batch, date, total marks
• Results: exam, student, marks obtained
8. Development Steps
1. Requirement analysis and design
2. Login and user roles
3. Student, teacher and batch management
4. Attendance module
5. Fees and accounts module
6. Exam and result module
7. Reports and dashboard
8. Testing and deployment
9. Future Ideas
• Online fee payment through bKash / Nagad
• Online classes and recorded videos
• Mobile app
• Automatic SMS and email notifications
• Online exams (MCQ)
10. Expected Benefits
• Saves time and reduces paper cost.
• Fewer accounting errors and easier collection of pending fees.
• Builds guardians' trust.
• Makes the coaching center more professional to run.
