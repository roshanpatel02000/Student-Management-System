Student Management System in C++
A lightweight, console-based CRUD (Create, Read, Update, Delete) application built in C. This project demonstrates the use of structs, arrays, loops, and soft-deletion logic to manage student records efficiently.

🚀 Features
Add Student: Register new students with a unique auto-incrementing Roll Number.
Display Records: View a list of all active student records.
Soft Delete: Remove students by Roll Number using an active flag (preserves data integrity).
Input Handling: Includes buffer clearing and string formatting to handle spaces in names.

🛠️ How it Works
The system uses a struct Student to organize data and a fixed-size array to store records.
Field              Description
rno         Unique identifier (Auto-incremented)
name        Student's full name (up to 50 characters)
std         The class/standard of the student
marks       Academic score
active     "Boolean flag (1 for active, 0 for deleted)"

📝 Usage Example
Select Option 1 to enter student details like Name, Class, and Marks.

Select Option 2 to see the list of added students.

Select Option 3 to "delete" a student. The program will ask for the Roll Number and mark that record as inactive.

Select Option 4 to exit
