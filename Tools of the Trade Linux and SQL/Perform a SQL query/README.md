# Perform-a-SQL-query

## Introduction
In this lab, you’ll learn how to retrieve information from a database using SQL. You’ll be using the MariaDB shell to run your SQL queries.

- What you’ll do
You have multiple tasks in this lab:
  - Return information on employee devices
  - Examine login attempts
  - Sort the data returned from a query
 
## Activity overview
Previously, you learned how to use basic SQL queries to retrieve information from a database. You have also learned about using the ORDER BY keyword to sort data returned in an ascending or a descending order.
In this lab activity, you’ll use SELECT and FROM in SQL to return the information you need from a database. You’ll also use the ORDER BY keyword to sequence the information returned by a query based on a specified column.
It's important to know how to query information from a database because this is a common task you might encounter as a security analyst. You should know how to get the information you need to improve security and keep data safe.
With that in mind, it's time to explore the scenario.

## Scenario
In this scenario, you have to determine which employee devices must be updated. You also need to investigate user login activity to explore if any unusual activity has occurred.
The information you need is located in the machines and login_attempts tables in the organization database.

Here’s how you’ll do this task: 
1. First, you’ll obtain information on the employee devices that must be updated.
2. Next, you’ll examine the login attempts for unusual activity.
3. Finally, you’ll use the ORDER BY keyword to sort the data returned by your SQL queries.

### Task 1. Retrieve employee device data
In this task, you need to obtain information on employee devices because your team needs to update them. The information you need is in the machines table in the organization database.
First, you need to retrieve all the information about the employee devices.

1. Run the following query to select all device information from the machines table:

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/eef65cd9-c2f2-4bbc-aed3-8797af86fab1)
![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/a657b6e3-6b3e-488e-9bb5-9dab3de7fa32)
![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/351e0aae-fd57-43ac-8ba1-a49ce1d09f26)
![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/3932d6b4-9f92-40c3-8532-26643c461790)
![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/58058ab0-3dc2-4bcc-ba2c-f25b9b15e4cd)

2. Run the following query to select only the device_id and email_client columns from the machines table. Replace X with device_id and Y with email_client:

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/39c25141-8b0a-4bba-b12d-08d769b72fc0)


![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/0e85a15a-34b3-4d0c-9811-d6934a83fefa)


3. Complete the query to return only the device_id, operating_system, and OS_patch_date columns from the machines table. Replace X, Y, and Z with the columns that you need to return:

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/7570d4fe-74a4-4edf-8cf7-477584facc61)


### Task 2. Investigate login activity

1. Write a SQL query to select the event_id and country columns from the log_in_attempts table.

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/b6efb639-d8c4-46d2-b7c2-c3b3d237461b)

2. Write a SQL query that selects the username, login_date, and login_time columns from the log_in_attempts table.

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/b252703c-4e9e-452e-843f-43430490de95)

3. Write a SQL query that selects all columns from the log_in_attempts table, using a single symbol after the SELECT keyword.

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/83b5ef3d-642c-4e8e-b252-ae49857531c6)

### Task 3. Order login attempts data

1. Run the following query, which orders log_in_attempts data by login_date:

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/2b34dd54-6e2d-40fc-8c9f-41f3d13e0f2e)

2. Modify the query from the previous step by adding the login time to the ORDER BY clause. You must replace X with the appropriate column name:

![image](https://github.com/roulthegr8/Perform-a-SQL-query/assets/90126847/bb4c70c7-abb1-4f58-9513-7384c099855a)

Notes :-

SELECT *
FROM machines;

SELECT device_id, email_client
FROM machines;

SELECT device_id, operating_system, OS_patch_date
FROM machines;

SELECT event_id, country
FROM log_in_attempts;

SELECT username, login_date, login_time
FROM log_in_attempts;

SELECT *
FROM log_in_attempts;

SELECT *
FROM log_in_attempts
ORDER BY login_date;

SELECT *
FROM log_in_attempts
ORDER BY login_date, login_time;





# Tools-of-the-Trade-Linux-and-SQL
 
