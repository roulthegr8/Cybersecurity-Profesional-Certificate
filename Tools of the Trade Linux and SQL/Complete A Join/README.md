# Complete A Join

## Introduction
In this lab, you’ll use INNER JOIN, LEFT JOIN, and RIGHT JOIN in SQL to retrieve information from two different tables. You’ll use these different types of SQL joins to join data from separate machines, employees, and login attempts tables. You’ll be using the MariaDB shell to run SQL queries.

What you’ll do

- You have multiple tasks in this lab:
  - Use an inner join to find information on employees and their machines
  - Use a left join and right join to find information on employees and their machines
  - Use an inner join to find information on employees and their login attempts
 
## Activity overview
As a security analyst, you’ll often find that you need data from more than one table.
Previously, you learned that a relational database is a structured database containing tables that are related to each other.
SQL joins enable you to combine tables that contain a shared column. This is helpful when you need to connect information that appears in different tables.
In this lab activity, you’ll use SQL joins to connect separate tables and retrieve needed information.

## Scenario
In this scenario, you’ll investigate a recent security incident that compromised some machines.
You are responsible for getting the required information from the database for the investigation.

Here’s how you’ll do this task: 
1. First, you’ll use an inner join to identify which employees are using which machines.
2. Second, you’ll use left and right joins to find machines that do not belong to any specific user and users who do not have any specific machine assigned to them.
3. Finally, you’ll use an inner join to list all login attempts made by all employees.

### Task 1. Match employees to their machines
First, you must identify which employees are using which machines. The data is located in the machines and employees tables.

You must use a SQL inner join to return the records you need based on a connecting column. In the scenario, both tables include the device_id column, which you’ll use to perform the join.

1. Run the following query to retrieve all records from the machines table:

![image](https://github.com/roulthegr8/Complete-a-join/assets/90126847/2123f8a3-be92-43f9-a3b2-e308cab879e5)


You’ll note that this query is not sufficient to perform the join and retrieve the information you need.

2. Complete the query to perform an inner join between the machines and employees tables on the device_id column. Replace X and Y with this column name:

![image](https://github.com/roulthegr8/Complete-a-join/assets/90126847/af5f2df0-ee24-4564-9b46-47bf830fdb35)

### Task 2. Return more data
You now must return the information on all machines and the employees who have machines. Next, you must do the reverse and retrieve the information of all employees and any machines that are assigned to them.

To achieve this, you’ll complete a left join and a right join on the employees and machines tables. The results will include all records from one or the other table. You must link these tables using the common device_id column.

1. Run the following SQL query to connect the machines and employees tables through a left join. You must replace the keyword X in the query:

![image](https://github.com/roulthegr8/Complete-a-join/assets/90126847/d64601a3-6b4a-433f-a64c-c2cf77c2ebd2)

2. Run the following SQL query to connect the machines and employees tables through a right join. You must replace the keyword X in the query to solve the problem:

![image](https://github.com/roulthegr8/Complete-a-join/assets/90126847/2be981e9-0a5c-4f20-afbc-c6c55d93bd7b)
   
### Task 3. Retrieve login attempt data
To continue investigating the security incident, you must retrieve the information on all employees who have made login attempts. To achieve this, you’ll perform an inner join on the employees and log_in_attempts tables, linking them on the common username column.

1. Run the following SQL query to perform an inner join on the employees and log_in_attempts tables. Replace X with the name of the right table. Then replace Y and Z with the name of the column that connects the two tables:

![image](https://github.com/roulthegr8/Complete-a-join/assets/90126847/902f5f2a-f519-453f-9530-02aa26abb7b5)
