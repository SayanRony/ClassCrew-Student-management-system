# ClassCrew: Student Management System 💻📚

A simple Student Management System built using C++ that allows adding, searching, updating, and displaying student information. This system utilizes Object-Oriented Programming (OOP) concepts like classes and file handling to store and manage student data in a text file. 🚀

## Features ✨
- **Add Student**: Adds a new student's details (Name, Roll Number, and CGPA) to a text file.
- **Search Student**: Search for a student by name and display their details.
- **Update Student**: Allows updating the CGPA of an existing student.
- **Display All Students**: Displays the details of all students stored in the file.

## OOP Concepts Used 🧑‍💻
- **Classes and Objects**: Used to define a `Student` class that encapsulates student details.
- **File Handling**: Reading and writing student data to a file to ensure data persistence.
- **Encapsulation**: Encapsulating student attributes like Name, Roll Number, and CGPA inside the `Student` class.

## Technologies 🛠️
- **C++** for core functionality.
- **Windows API** for clearing screen (`system("cls")`) and sleep (`Sleep()`).
- **File handling** using C++ file streams (`ifstream` and `ofstream`).

## Code Flow 🔄
1. **Add Student**: The user is prompted to enter the student's name, roll number, and CGPA. These details are then appended to a text file.
2. **Search Student**: The user enters the name of the student, and the system checks if the name exists in the file, displaying the student's details if found.
3. **Update Student**: The user provides the roll number of a student. If the student is found, their CGPA is updated.
4. **Display All Students**: Displays a list of all students stored in the file.

## File Format 📄
- Each student's information is stored in a file called `Student.txt`.
  
