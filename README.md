# django-traineeship-system

This project is a comprehensive Student Management System developed using Python with the Django framework, designed for educational purposes.


## Features

 Admin Users
- Overview Dashboards: View summary charts for student performance, staff performance, and course statistics.
- Staff Management: Add, update, and delete staff members.
- Student Management: Add, update, and delete student records.
- Course Management: Add, update, and delete courses.
- Subject Management: Add, update, and delete subjects.
- Session Management: Add, update, and delete academic sessions.
- Attendance Monitoring: View and manage student attendance

Staff/Teachers

- Summary Charts: Access charts related to students, subjects, and leave status.
- Attendance Management: Record and update student attendance.
- Results Management: Add and update student results.

Students

- Summary Charts: View charts related to attendance, subjects, and leave status.
- Attendance View: Check personal attendance records.
- Results View: Access academic results.



## Prerequisites

- Git: Version control system
    - Download Git
- Python: Latest version
    - Download Python
- Pip: Python package manager
    - Pip Installation Guide

## Installation

1. Create a Directory for the Project

```bash
  mkdir django-student-management-system
  cd django-student-management-system
```
2. Set Up a Virtual Environment

```bash
  pip install virtualenv
```
```bash
  python -m venv venv
```
```bash
  venv\Scripts\activate
```
3. Clone the Repository
```bash
  git clone https://github.com/yourusername/django-student-management-system.git
  cd django-student-management-system
```
4. Install Project Dependencies

```bash
  pip install -r requirements.txt
```

5. Configure Allowed Hosts in settings.py  (not necessary)

```bash
  ALLOWED_HOSTS = ['*']
```

6. Run the Development Server

```bash
  python manage.py runserver
```

7. Create a Superuser

```bash
    python manage.py createsuperuser
```
Follow the prompts to set up the superuser credentials.


## Default credentials 

- HOD/SuperAdmin

    - Email:     admin@gmail.com
    - Password:  admin
    
- Staff/teacher

    - Email:     staff@gmail.com
    - Password:  staff

- Student

    - Email:     student@gmail.com
    - Password:  student

## License

[MIT](https://choosealicense.com/licenses/mit/) This project is licensed under the MIT License. See the LICENSE file for details.

Copyright © 2022 @ritikbanger

Permission is granted, free of charge, to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the following conditions:

Include the copyright notice and permission notice in all copies or substantial portions of the Software.
The Software is provided "as is", without warranty of any kind. The authors or copyright holders are not liable for any claims, damages, or other liabilities.

