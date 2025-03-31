##MotorPH Payroll System
This is a simple payroll system made for MotorPH using Electron.js. It helps with managing employees, attendance, and salaries.

If you want video instructions: https://drive.google.com/file/d/1kno2F2mCE3Vtspz3Mp_mKYAF-93EYPEd/view?usp=sharing

NOTE: The database is saved on the system. if you want to start with clean database follow these instructions 

🔽🔽🔽

##To Reset/Flush Database (For Testing)
To reset the database and start fresh with testing:

1. Navigate to the `database` folder in your project directory
2. Delete the existing `database.db` file
3. Restart the application - a new database will be automatically created
4. Import the fresh data files as described in the "To Import Data" section above

This will allow you to start with a clean database for testing purposes.

📍#Features
Log in for Employees and HR – Employees and HR staff have separate logins.

Employee Management – HR can add, update, and manage employee details.

Attendance Records – Keeps track of employee attendance.

Payroll Generation – Automatically calculates salaries based on attendance.

Government Deductions – Computes SSS, PhilHealth, Pag-IBIG, and withholding tax.

HR Dashboard – A summary page for HR to see payroll and employee data.

Employee Portal – Employees can check their salary and attendance records.

📍To use:

1.) download the file from github

2.) Extract file

3.) type "cmd" inside the file directory

4.) type "npm install" and wait for the installation to be completed

5.) type "npm start"

📍#Log In Details (For Testing)

HR Login:

Username: admin

Password: motorph

Employee Login:

Employee #: 100XX (replace XX with actual numbers)

Password: motorph


📍##To Import Data

Option 1.(Recommended) Inside the extracted file locate the Employee_Details/Attendance folder to access the files. Import the MotorPH Employee Data.xlsx for Emloyee details and Attendance.xlsx for attendance record

Option 2.) For employee Details: You can import the database from the website https://docs.google.com/spreadsheets/d/189fvPCZS7JKMBYos00ZEoApqnBB05jAjy2vak6lD4g0/copy and download it as .xlsx file

For the Attendance Record you must download the database without the employee details. I have a existing file on MotorPH_Payroll>Attendance>Attendance.xlsx or you can just download this: https://docs.google.com/spreadsheets/d/1kx5ym73lv7z3tLfddxjZFWOGCzpW0uF180ybw_AgHU4/edit?usp=sharing

