# Student Management System 
This is a Simple Student Management System, which allows the student, professor as well as the administration staff to perform CRUD operations

## Motivation
We felt that students don’t get much clarity and ease while obtaining their marks and results in various subjects and for teachers it gets especially difficult to manage so many subject marks and grades for hundreds of students. Due to this sometimes result gets delayed or even in some cases misplaced which affect both the students and the teachers.

We thought to solve this problem by building a management system that will serve as a ecosystem for both the teachers and students, and provide various useful features by taking help of modern day technology.

This will be a one stop solution for the teachers as well as the students, instead of maintaining and following the older norms of storing records in files, this will aim at automating it for the mutual benefit of both

## Features of this Project

### A. Admin Users Can
1. See Overall Summary Charts of Stuudents Performance, Staffs Perfomrances, Courses, Subjects, Leave, etc.
2. Manage Staffs (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review and Reply Student/Staff Feedback
9. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave
5. Send Feedback to HOD

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave
5. Send Feedback to HOD


## How to Run this project?

**Run Server**

Command for PC:
```python
$ python manage.py runserver
```

**Login Credentials**

Create Super User (HOD)
```
$  python manage.py createsuperuser
```
Then Add Email, Username and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@gmail.com
Password: admin

*For Staff*
Email: staff@gmail.com
Password: staff

*For Student*
Email: student@gmail.com
Password: student


