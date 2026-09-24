# Student Grades Management System

A simple command-line application written in Python to manage student grades.

The application stores student names and their grades in a Python dictionary and provides options to:

* Add a new student
* Update an existing student's grade
* Delete a student
* View all students and their grades
* Exit the program

## Project Structure

```text
student-grades-management-system/
│
├── student_grades.py
└── README.md
```

## Requirements

Before running the project, make sure you have:

* Python 3.8 or higher
* A terminal or command prompt
* Git (optional, if cloning the repository)

This project uses only Python's built-in features, so **no external dependencies are required**.

## Setup Instructions

### 1. Clone the Repository

Open a terminal and run:

```bash
git clone <YOUR_REPOSITORY_URL>
```

Replace `<YOUR_REPOSITORY_URL>` with the URL of your GitHub repository.

Then move into the project directory:

```bash
cd student-grades-management-system
```

### 2. Check Python Installation

Verify that Python is installed:

```bash
python --version
```

If your system uses `python3`, run:

```bash
python3 --version
```

Python 3.8 or higher is recommended.

### 3. Create a Virtual Environment

Creating a virtual environment is recommended even though this project has no external dependencies.

On Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

On macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

There are no third-party dependencies for this project.

Therefore, no `pip install` command is required.

## Configuration

No configuration files, API keys, databases, or environment variables are required.

Student data is stored temporarily in an in-memory Python dictionary:

```python
student_grades = {}
```

**Note:** All student data will be lost when the program is closed.

## Running the Project

Run the Python file from the project directory:

```bash
python student_grades.py
```

On systems where `python3` is required:

```bash
python3 student_grades.py
```

## How to Use

After starting the program, you will see a menu similar to:

```text
Student Grades Management System

1. Add Student
2. Update Student
3. Delete Student
4. View Student
5. Exit
```

### Add Student

Select option `1` and enter the student's name and grade.

Example:

```text
Enter your choice = 1
Enter student name = Sreejita
Enter student grade = 100
Added Sreejita with a 100
```

### Update Student

Select option `2` and enter the student's name and new grade.

```text
Enter your choice = 2
Enter student name = Sreejita
Enter student grade = 95
Sreejita with marks are updated 95
```

### Delete Student

Select option `3` and enter the student's name.

```text
Enter your choice = 3
Enter student name = Sreejita
Sreejita has been successfully deleted
```

### View Students

Select option `4` to display all students and their grades.

```text
Sreejita : 100
Rahul : 85
Priya : 92
```

If there are no students:

```text
No students found/added
```

### Exit

Select option `5` to close the program.

```text
Closing The Program.....
```

## Features

* Simple command-line interface
* Add student grades
* Update student grades
* Delete student records
* Display all student records
* Uses Python dictionary for data storage
* No external libraries required

## Technologies Used

* Python 3
* Python Dictionary
* Functions
* Conditional Statements
* Loops
* User Input

## Limitations

* Data is stored only in memory.
* Student records are not saved permanently.
* The program does not use a database or file storage.
* Grades are expected to be entered as integers.

## Future Improvements

Possible improvements include:

* Save student records to a file
* Add database support
* Validate grade ranges
* Prevent duplicate student entries
* Add search functionality
* Calculate average grades
* Display highest and lowest grades
* Add a graphical user interface

## License

This project is available for educational and learning purposes.
