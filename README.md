# searchsallery-file

                     TUTORIAL 7
—-----------------------------------------------------------------------
Name:- Abhay Dubey
Roll No :- 1131
PRN :- BE25CE1131
Batch :- C
ACTIVITY 7

Create a C program to perform various file operations, including reading
from a file, writing to a file, and displaying the contents of a file. The
program should provide options for the user to select the desired operation
from a menu. Upon selecting an operation, the program should execute the
corresponding functionality using appropriate file handling techniques.
Additionally, the program should handle errors such as file not found or
permission issues gracefully and provide informative messages to the user.


1. Purpose
The program demonstrates how to build a simple employee database system using file handling in C. It allows users to:
Add employee records (name and salary).
Search for an employee’s salary by name.
Exit the program.
2. Core Concepts Involved
🔹 File Handling
Files are used to store employee data permanently.
Two modes are used:
Append mode ("a") → Adds new records without deleting existing ones.
Read mode ("r") → Reads existing records for searching.
🔹 Strings and Input
Employee names are stored as character arrays (char name[M]).
scanf is used for input, but it only reads single-word names (no spaces).
🔹 Control Structures
Loops (do...while) → Used in addEmployees() to allow multiple entries.
Conditionals (if...else) → Used in main() to handle menu choices and in searchSalary() to check if the employee exists.
🔹 Functions
addEmployees() → Handles adding new records.
searchSalary() → Handles searching for a salary.
main() → Provides the menu and controls program flow.
3. Program Flow (Theory)
The program starts and displays a menu.
Based on user choice:
Option 1: Calls addEmployees() → Prompts for name and salary → Stores them in the file.
Option 2: Calls searchSalary() → Prompts for name → Searches file → Displays salary if found.
Option 3: Exits the program.
Any other input → Displays an error message.
File is closed after each operation to ensure data integrity.
4. Advantages
Simple and easy to implement.
Demonstrates basic file handling.
Data persists even after program termination.
5. Limitations
Names cannot contain spaces.
No validation for salary input.
Only exact name matches are supported.
No options to update or delete records.
Data stored in plain text (not secure).
6. Possible Enhancements
Use fgets for names with spaces.
Add error handling for file operations.
Implement update and delete features.
Use binary files for efficiency and security.
Add listing and sorting of employees.
By google , wikipidea ,youtub
