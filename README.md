# CONSOLE-BASED-University-Management-System
##🎓 CONSOLE-BASED-UNIVERSITY-MANAGEMENT-SYSTEM
 This Python-based console application simulates a basic University Management System, allowing users to manage students, faculty, and courses through a text-based menu interface. It's designed for learning and understanding core concepts like object-oriented programming, file handling, and user interaction through the console.

##✅ Features
- Add, update, delete student and faculty records

- Manage courses and enrollments

- Display and search student performance reports

- Role-based access: Admin, Faculty, and Student views

- Menu-driven CLI for smooth navigation

- Simple data storage using text or JSON files

## Prerequisites
- Python 3 installed on your system
- Basic knowledge of Python, OOP, and file handling
- Required Python libraries (mostly built-in):
    ```sh
    pip install json datetime prettytable
      ```
 ## How to Use
 1.Clone the repository:
    ```sh
    git clone https://github.com/your-username/university-management-system.git
cd university-management-system
     ```
 2.Run the script:
       ```sh
       python main.py
 3.Follow the on-screen menu to perform tasks like adding students, enrolling in courses, or 
   generating reports.
   
## Code Explanation
- The application uses object-oriented programming to represent entities like Students, Faculty, 
  and Courses.

- A menu-driven interface makes it easy to interact with the system.

- Data is stored using simple file I/O or JSON for persistence.

- Role-specific options are displayed based on user login (Admin/Faculty/Student).

- Modules are separated for better readability (e.g., student.py, faculty.py, course.py).

## Security Considerations
- Sensitive actions like data modification are restricted to Admin users.
- You can integrate authentication using basic password matching or extend it with hashed 
   passwords and login attempts.
- For better data security, consider adding file encryption or migrating to a database like 
  SQLite or MySQL.

## Future Enhancement
- Add GUI support using Tkinter or PyQt
- Integrate a relational database (e.g., SQLite/MySQL) for better data management
- Implement user authentication and session handling
- Export reports to PDF or Excel formats




