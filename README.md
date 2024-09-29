
```markdown
# Student and Library Management Systems (C++ & MySQL)

This repository contains two distinct management systems developed using C++ and MySQL. Each system showcases object-oriented programming in C++ alongside database integration using MySQL. The systems are:

1. **Student Management System** - A basic system for managing student data, including adding, displaying, searching, updating, and deleting student records.
2. **Library Management System** - A system for managing library books and student borrowing records, allowing for the addition of books and students, as well as borrowing functionality.

## Project Structure

### 1. Student Management System

The **Student Management System** provides administrators the ability to:
- Insert student data (ID, Name, Subject, CGPA)
- Display all student records
- Search for a student by ID
- Update a student's subject by ID
- Delete a student record

#### Key Classes
- `University`: Manages student details such as ID, Name, Subject, and CGPA.

#### Database Table Structure
- **Table Name**: `student`
  - **Columns**:
    - `Id` (INT): Student ID
    - `Name` (VARCHAR): Student Name
    - `Subject` (VARCHAR): Student's Subject
    - `CGPA` (FLOAT): Student's CGPA

### 2. Library Management System

The **Library Management System** allows for:
- Admin functions to add books and register students
- User functionality to borrow books, with a check for book availability
- Displaying available books in the library

#### Key Classes
- `Library`: Manages library book details such as name and quantity.
- `Student`: Manages student IDs for borrowing purposes.

#### Database Table Structure
- **Table Name**: `lib` (Books)
  - **Columns**:
    - `Name` (VARCHAR): Book Name
    - `Quantity` (INT): Number of Copies Available
- **Table Name**: `student` (Student Records)
  - **Columns**:
    - `Id` (VARCHAR): Student ID

## Technologies Used
- **C++**: For developing the system's logic and user interface.
- **MySQL**: For database storage and management of student and library records.
- **Windows API**: For creating a console-based interface.

## How to Use

### Prerequisites
- Install MySQL Server and create the necessary databases (`my_cpp`) and tables (`student`, `lib`).
- Compile and run the C++ code using any IDE such as Visual Studio Code or Code::Blocks with MySQL connector installed.

### Running the Systems
1. Clone the repository.
2. Open the project in your IDE.
3. Ensure the MySQL server is running and the database is properly configured.
4. Compile and run the desired system (Student or Library Management).

## Future Improvements
- Enhance the user interface by integrating a graphical interface (e.g., Qt or a web-based UI).
- Add login and authentication features for both systems.
- Extend the library system to handle book returns and fines.

## License
This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to contribute to this project by submitting a pull request or reporting any issues!
```

This file highlights both systems' functionality and provides a clear guide for users and contributors.
