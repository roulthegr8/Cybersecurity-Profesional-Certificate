# Apply more filters in SQL

## Introduction
In this lab, you’ll apply more filters to SQL queries to retrieve information from a database. You’ll use common operators in SQL to filter by specific dates and times. You’ll be using the MariaDB shell to run your SQL queries.

What you’ll do
You have multiple tasks in this lab: 
  - Filter for login attempts made after a certain date
  - Filter for login attempts made in a certain date range
  - Filter for login attempts made at a certain time
  - Filter for login attempts by ID

## Activity overview
As a security analyst, you’ll often need to query numbers and dates.

For example, you may need to filter patch dates to find machines that need an update. Or you might filter login attempts made during a certain period of time to investigate a security incident.

Common operators for working with numeric or date and time data will help you accurately filter data. These are some of the operators you'll use:

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/c8829cb1-9ea1-49b8-89bf-59c7abbbd4ed)

In this lab activity, you’ll apply these operators to accurately filter for specific numbers and dates!

## Scenario
In this scenario, you’re investigating a recent security incident.

You need to gather information about login attempts for certain dates and times. This will help in resolving a security incident.
Here’s how you’ll do this task: 
1. First, you’ll retrieve login events made after a certain date.
2. Second, you’ll narrow the focus of the search to filter logins in a date range.
3. Third, you’ll investigate logins that were made at certain times.
4. Finally, you’ll filter login attempts based on their event IDs.

It's time to get started and use operators to filter data from a table!

### Task 1. Retrieve login attempts after a certain date
In this task, you need to investigate a recent security incident. To do this, you need to gather information about login attempts made after a certain date.

1. Complete the SQL query to retrieve data for login attempts made after '2022-05-09'. Replace X with the correct operator:

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/a3339d7d-86b3-44e9-adcd-acc8bff7221c)

Now, based on your first query, you find a need to expand the date range to include 2022-05-09 in your search.

2. Complete the SQL query to retrieve data for login attempts that were made on or after '2022-05-09'. Replace X with the correct operator:

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/ee557170-61e7-4b14-a1d8-9bc0abec680d)

Task 2. Retrieve logins in a date range
In this task, you need to narrow the focus of the search. Login attempts made after 2022-05-11 shouldn't be included. Use the BETWEEN and AND operators to return results between '2022-05-09' and '2022-05-11'.

- Run the query to retrieve the required records. You must insert the required dates X and Y:

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/aa853222-ce4f-4ffe-8808-6cca1d5ee82e)

Task 3. Investigate logins at certain times
In this task, you need to investigate logins that were made at certain times. To do this, filter the data in the log_in_attempts table by login time (login_time).

First, your organization's typical work hours begin at 07:00:00. Retrieve all login attempts made before 07:00:00 to learn more about the users who are logging in outside of typical hours.

1. Write a SQL query to retrieve data for login attempts made before '07:00:00'.

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/e8360af1-e290-4141-8caf-1983889f8fdc)

2. Modify the query to return logins between '06:00:00' and '07:00:00'

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/237857dc-42f1-4a3b-82c7-f62b1f564360)

### Task 4. Investigate logins by event ID
In this task, you need to investigate login attempts based on event ID numbers. With this query, you want to return only the event_id, username, and login_date fields from the log_in_attempts table.

1. Write a query to return login attempts with event_id greater than or equal to 100.

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/76b0a9ab-c019-4f77-8303-b874a1115165)

2. Modify the query to return only login attempts with event_id between 100 and 150.

![image](https://github.com/roulthegr8/Apply-more-filters-in-SQL/assets/90126847/c1d3598d-8be2-4ac5-ae7e-eb425196d574)

### Notes
[Notes.txt](https://github.com/roulthegr8/Apply-more-filters-in-SQL/files/12447788/Notes.txt)



# Tools-of-the-Trade-Linux-and-SQL
 
