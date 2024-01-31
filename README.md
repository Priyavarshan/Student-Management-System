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

## Screenshots
# Adding New Record:

![Screenshot 2024-01-31 203850](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/6b1e17d5-71a2-4354-983a-2a8321babdb6)

![Screenshot 2024-01-31 204046](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/e9226e47-b17c-4993-a9a7-1ecd48d8a04f)

# Displaying Records:

![Screenshot 2024-01-31 205016](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/38cc04f2-59b7-469a-87d1-6ac7d6fed1e1)

# Updating Record:

![Screenshot 2024-01-31 210337](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/c698bbdd-b331-436d-8a28-e3c170b7eaa6)

![Screenshot 2024-01-31 210511](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/abbf26d4-bb2f-4cea-953a-04183060aaed)

# Deleting Record:

![Screenshot 2024-01-31 211006](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/d2c8bb73-9423-4eac-8d93-c2e522d6d181)

# Searching Record:

![Screenshot 2024-01-31 212537](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/7259f383-9e5c-41c1-acf4-f3c8250069cb)

![Screenshot 2024-01-31 211645](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/4d1b0cea-2d52-4028-af36-ea1c181b223c)

# Resetting Form:

![Screenshot 2024-01-31 211841](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/bd8302f0-e907-44d9-9562-bea887e0e61c)

# Exiting Application:

![Screenshot 2024-01-31 212032](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/ed076b45-c670-40b4-80d2-a929ae02b6a5)

# Displaying Records from MySQL Database:

![Screenshot 2024-01-31 213809](https://github.com/Priyavarshan/Student-Management-System/assets/110277933/4bc3ee45-7c0a-4af7-95f2-0e5d6a9242e6)
