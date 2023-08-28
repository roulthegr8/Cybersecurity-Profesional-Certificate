# Filter with AND, OR, and NOT

## Introduction
In this lab, you’ll use the AND, OR, and NOT operators in SQL to filter for information. You’ll use SQL to get specific information about employees, their machines, and the departments they’re in. You’ll be using the MariaDB shell to run SQL queries.

What you’ll do
You have multiple tasks in this lab:
  - Filter for login attempts that occurred after hours
  - Filter for login attempts on specific dates
  - Filter for login attempts from specific locations
  - Filter for information on employees in specific departments
  - Filter for information on employees not in a specific department

## Activity overview
As a security analyst, you’ll likely need to analyze data. And often finding the specific data you’ll need depends on more than one factor.
To retrieve specific pieces of information from the database, you can filter for multiple conditions. You can also filter for what does not match a particular condition.
In this lab activity, you’ll use the AND, OR, and NOT operators to create more complex filters for SQL queries.
Get ready to practice running a few complex SQL queries!

## Scenario
In this scenario, you need to obtain specific information about employees, their machines, and the departments they belong to from the database.
Your team needs data to investigate potential security issues and to update computers.
You are responsible for filtering the required information from the database.

Here’s how you’ll do this task: 
1. First, you’ll retrieve all failed login attempts after business hours.
2. Second, you’ll retrieve all login attempts that occurred on specific dates.
3. Third, you’ll retrieve logins that didn't originate in Mexico.
4. Fourth, you’ll retrieve information about certain employees in the Marketing department.
5. Fifth, you’ll retrieve information about employees in the Finance or the Sales department.
6. Finally, you’ll obtain information about employees who are not in the Information Technology department.


### Task 1. Retrieve after hours failed login attempts
Your team is investigating failed login attempts that were made after business hours. You want to retrieve this information from the login activity. You’ll identify all unsuccessful attempts after 18:00.

The login_time column in the log_in_attempts table contains information on when login attempts were made. Office hours end at '18:00'.

The success column in the log_in_attempts table contains values of TRUE or FALSE to indicate whether the login was successful. MySQL stores Boolean values as 1 for TRUE, and 0 for FALSE. This means that TRUE is represented as 1, and FALSE represented as 0 in the success column.

Use the AND operator to retrieve the failed login attempts that occurred after business hours. Replace the X and Y with the correct values to filter for the records you need:

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/7df1bfa3-d912-4790-887d-da3102e89152)


### Task 2. Retrieve login attempts on specific dates
Your team is investigating a suspicious event that occurred on '2022-05-09'. You want to retrieve all login attempts that occurred on this day and the day before ('2022-05-08').

The login_date column in the log_in_attempts table contains information on the dates when login attempts were made.

Use the OR operator to retrieve the failed login attempts on the specified days. Replace the X and Y with the correct values to filter for the records you need:

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/ceb76e9e-9ba1-4d3e-85b4-a62ffc2752b0)

### Task 3. Retrieve login attempts outside of Mexico
Now, your team is investigating logins that did not originate in Mexico, and you need to find this information. Note that the country field includes entries with 'MEX' and 'MEXICO'. You should use the NOT and LIKE operators and the matching pattern 'MEX%'.

Run the following SQL query to retrieve login attempts that did not originate in Mexico. Replace X with the correct operator and Y with the correct pattern to filter for the information you need:

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/830e43c1-c6b8-43f5-9a2c-5ed0f5a00034)

### Task 4. Retrieve employees in Marketing
For tasks 4, 5 and 6 you need to retrieve the information from the department and office columns in the employees table.

You can run the following SQL query if you need to view the columns and values in the employees table:

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/026f4fb2-e236-4d3a-a109-f014ecaf7d8c)


### Task 5. Retrieve employees in Finance or Sales
Now, your team needs to perform a different update to the computers of all employees in the Finance or the Sales department, and you need to locate information on these employees.

Write a SQL query to retrieve records for employees in the 'Finance' or the 'Sales' department.

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/a7b04ba3-2783-4111-8e4a-401fe3272ee6)


### Task 6. Retrieve all employees not in IT
Your team needs to make one more update. This update was already made to employee computers in the Information Technology department. The team needs information about employees who are not in that department. You should use the NOT operator to identify these employees.

Write a SQL query to retrieve records for employees who are not in the 'Information Technology' department.

![image](https://github.com/roulthegr8/Filter-with-AND-OR-and-NOT/assets/90126847/88c42afe-090f-474c-9dd0-b094ae02a4c5)


