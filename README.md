# payroll-calculation-with-overtime

** Overview **

This is a Python-based payroll calculation system that calculates the total pay for an employee, including overtime pay. The program asks for the number of hours worked for 5 days and the hourly wage, then calculates the regular pay and overtime pay (if any) based on a 40-hour workweek. The payroll information is then stored in a text file.

** Features **

User inputs the number of hours worked each day (up to 5 days).
Validates the input to ensure hours are between 0 and 24.
Calculates total pay, including overtime (if applicable).
Overtime pay is calculated at a rate of 1.5x for hours worked over 40.
The results are stored in a payroll_info.txt file for easy access.

** How to Use **

Clone this repository to your local machine.
Run the Python script payroll_system.py.
Enter the hourly wage and the hours worked for each day.
The program will display the total hours, regular pay, overtime pay (if applicable), and total pay.
A text file payroll_info.txt will be created with all the payroll details.

** Example **
If your hourly wage is $30 and you worked the following hours for 5 days:

Day 1: 10 hours
Day 2: 10 hours
Day 3: 10 hours
Day 4: 8 hours
Day 5: 5 hours
You will have worked a total of 43 hours. Since 40 hours is the normal workweek:

Regular pay: 40 * $30 = $1200
Overtime pay: 3 * $30 * 1.5 = $135
Total pay: $1200 + $135 = $1335
The payroll_info.txt file will include:
