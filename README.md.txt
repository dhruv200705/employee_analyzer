Employee Management System
Project Overview
The Employee Management System is a beginner-friendly Python project
that demonstrates Object-Oriented Programming (OOP) concepts. It allows
users to create and display records for Persons, Employees, and Managers
through a simple menu-driven program.

Features
Create a Person record with a name and age.
Create an Employee record with a name, age, employee ID, and salary.
Create a Manager record with a name, age, employee ID, salary, and
department.
Display saved Person, Employee, and Manager details.
Use a simple menu to select operations.
Show a message when no records are available.
OOP Concepts Used
This project demonstrates:

Class and Object: Person, Employee, and Manager are
classes used to create objects.
Inheritance: Employee inherits from Person, and Manager
inherits from Employee.
Constructor (__init__): Initializes object data.
super(): Calls the constructor of the parent class.
Method Overriding: Each class defines its own show_details()
method.
Lists: Stores Person, Employee, and Manager objects while the
program is running.
Class Structure
Person
  |
Employee
  |
Manager
Technologies Used
Python 3
Object-Oriented Programming (OOP)
Python lists
Project File
Employee-Management-System/
│
├── employee.py
└── README.md


Option Operation

1 Create a Person
2 Create an Employee
3 Create a Manager
4 Show Details
5 Exit

When you select Show Details, choose Person, Employee, or Manager to
display the records of that type.

Example
--- Python OOP Project: Employee Management System ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Show Details
5. Exit
Important Note
Records are stored in Python lists while the program is running. They
are not saved to a file or database, so the records will be lost when
the program is closed.

Future Improvements
Save records permanently using a file or database.
Add options to update and delete records.
Add input validation for age and salary.
Improve the menu and user interface.
Author
Created as a Python Object-Oriented Programming practice project.

