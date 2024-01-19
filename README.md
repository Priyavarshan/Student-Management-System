# MySQL Connector - Student Management System
This Python script implements a simple Student Management System using the Tkinter GUI toolkit and MySQL database for data storage.

## Features
- Add new student records
- Display all student records
- Update existing student records
- Delete student records
- Search for specific student records
- Reset the input fields
- Exit the application

## Requirements
- Python 3.x
- Tkinter library
- MySQL database

## How to Use

1. Install the required libraries:

   ```bash
   pip install pymysql
   ```

2. Ensure you have a MySQL server running with the necessary database (in this case, 'python_db').

3. Update the MySQL connection details in the script:

   ```python
   sqlCon = pymysql.connect(host="localhost", user="root", password="123456", database="python_db")
   ```

4. Run the script:

   ```bash
   python Student.ipynb
   ```

5. Use the GUI to perform various operations on student records.

## Author
Priyavarshan R G
