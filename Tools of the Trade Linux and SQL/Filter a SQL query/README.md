# Filter-a-SQL-query

## Introduction
In this lab, you’ll apply basic filters to SQL queries to retrieve information from a database. You’ll use SQL to get specific information about employees, their machines, and the departments they’re in. You’ll be using the MariaDB shell to run SQL queries.

What you’ll do :-

You have multiple tasks in this lab:

  - Return information on machines and their operating systems
  - Filter for machines with a specific operating system
  - Filter for employees in specific departments
  - Filter for employees who use specific machines

## Activity overview
As a security analyst, knowing how to make better queries to retrieve specific pieces of data can help you find the security-related information you need more efficiently.

In this lab activity, you’ll apply basic filters to SQL queries to retrieve information from a MariaDB database.

MariaDB is a popular open source relational database that is compatible with MySQL.

This activity provides you with a great opportunity to apply what you’ve learned and add filters to SQL queries.

## Scenario
In this scenario, you need to get specific information about employees, their machines, and the departments they’re in. Your team needs this data to perform various tasks, such as running updates, posting a privacy notice in certain departments, and sending an alert to an employee with an issue on a machine.

You are responsible for finding the required information by querying a database. You’ll add filters to your queries to locate the information more quickly.

Here’s how you’ll do this task: 
1. First, you’ll list all organization machines and their operating systems.
2. Second, you’ll list all machines with the operating system OS 2.
3. Third, you’ll list all the employees in the Finance and Sales departments.
4. Fourth, you’ll obtain information about machines.

### Task 1. List all organization machines
In this task, you need to get a list of all organization machines and their operating systems. The data is contained in the machines table. You’ll need to use the SELECT keyword to return specific columns.

- Run a SQL query to retrieve only the device_id and operating_system columns from the machines table.

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/035a9ec7-fc9d-4859-baa5-fac6f08cfe02)

### Task 2. Retrieve a list of the machines with OS 2

In this task, you need to obtain a list of all machines with the 'OS 2' operating system because these machines need an update. To get this information, you’ll run your first SQL query with a filter.

- Select all the records from the machines table with a value of 'OS 2' in the operating_system column. Replace the value X with the correct string:

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/13db809a-d619-4c7b-9cb1-92323cacda70)

### Task 3. List employees in specific departments

In this task, you need to retrieve a list of all the employees in the Finance and Sales departments to obtain their office numbers. A notice about handling confidential financial information will be posted to these offices.

1. Filter the rows returned from department column in the employees table to include only employees from the 'Finance' department. Replace X with the appropriate column name and Y with the appropriate value to complete the filter:

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/78fe560e-f2aa-473f-b284-c37ede97f84e)

2. Modify the previous query so that it returns employees who are in the 'Sales' department.

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/3326b3f5-c615-4a50-a4a7-2ef3d5ab2e9e)

### Task 4. Identify employee machines

Your team recently discovered that there are issues with machines in the South building. In this task, you need to obtain certain employee and computer information.

A machine in 'South-109' has an issue. You need to determine which employee uses that computer so you can send them an alert.

1. Write a query to identify which employee uses the office in 'South-109'. (The data must be returned from the office column in the employees table.)

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/0bcc4b3c-d29e-4ab9-b2bf-1d7a642e59d6)

Next, your team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, 'South-109').

2. Modify the query you used in the previous step so that it returns information on all the employees in the 'South' building. Use the LIKE operator with % in this query.

![image](https://github.com/roulthegr8/Filter-a-SQL-query/assets/90126847/7df4f5d2-da61-4bb8-b981-44c9259c7ec6)

### NOTES
[FILTER SQL QUERY.txt](https://github.com/roulthegr8/Filter-a-SQL-query/files/12447722/FILTER.SQL.QUERY.txt)


