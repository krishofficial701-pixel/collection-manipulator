

# Student Data Organizer

This is a simple Python program to manage student information.

## Features

The program provides these options:

1. **Add Student** – Add a student's ID, name, age, grade, date of birth, and subjects.
2. **Display Students** – Show all stored student information.
3. **Update Student** – Update a student's age and grade.
4. **Delete Student** – Delete a student using their ID.
5. **Display Subjects** – Display all subjects offered by the students.
6. **Exit** – Exit the program.

## Concepts Used

This project uses basic Python concepts:

* Lists
* Dictionaries
* Tuples
* Sets
* `while` loop
* `for` loop
* `if-elif-else`
* User input
* String operations

## How to Run

1. Install Python on your computer.
2. Copy the program into a Python file.
3. Save it as:

```text
student_data_organizer.py
```

4. Run the program:

```bash
python student_data_organizer.py
```

## Example

```text
Welcome to the Student Data Organizer!

1. Add Student
2. Display Students
3. Update Student
4. Delete Student
5. Display Subjects
6. Exit

Enter choice: 1

Student ID: 101
Name: Krish
Age: 18
Grade: A
Date of Birth: 05-08-2008
Subjects: Python,C,Math

Student added!
```

## Data Structure

Each student is stored using a dictionary.

```python
student = {
    "info": (id, dob),
    "name": name,
    "age": age,
    "grade": grade,
    "subjects": subjects
}
```

The students are stored inside a list:

```python
students = []
```

## Author

Created as a basic Python programming project.
