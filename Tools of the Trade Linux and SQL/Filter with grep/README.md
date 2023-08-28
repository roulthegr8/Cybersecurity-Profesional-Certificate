# Filter-with-grep

Tools of the Trade: Linux and SQL > Week 3 Activity: Filter with grep

## Introduction
In this lab, you’ll learn how to use the grep command and piping to search for files and return specific information. You’ll get information from different files, including server log files and user data files. You’ll use Linux commands in the Bash shell to complete these steps.

What you’ll do. You have multiple tasks in this lab:
 1. Search for error messages in a file
 2. Search for files that contain a specific string
 3. Search for information in user files

## Activity overview
Previously, you learned about tools that you can use to filter information in Linux. You’re also familiar with the basic commands to navigate the Linux file system by now.
In this lab activity, you’ll use the grep command and piping to search for files and to return specific information from files.
As a security analyst, it’s key to know how to find the information you need. The ability to search for specific strings can help you locate what you need more efficiently.

## Scenario
In this scenario, you need to obtain information contained in server log and user data files. You also need to find files with specific names.

Here’s how you’ll do this:
 1. First, you’ll navigate to the logs directory and return the error messages in the server_logs.txt file.
 2. Next, you’ll navigate to the users directory and search for files that contain a specific string in their names.
 3. Finally, you’ll search for information contained in user files.With that in mind, you’re ready to practice what you've learned.

Note: The lab starts with your user account, called analyst, already logged in to a Bash shell. This means you can start with the tasks as soon as you click the Start Lab button.

-------------

### Task 1. Search for error messages in a log file
In this task, you must navigate to the /home/analyst/logs directory and report on the error messages in the server_logs.txt file. You’ll do this by using grep to search the file and output only the entries that are for errors.

 1. Navigate to the /home/analyst/logs directory.

 ![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/c8290bdb-1b9d-45a0-8681-5877ae6393a5)

 
 2. Use grep to filter the server_logs.txt file, and return all lines containing the text string error.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/e808c528-caa5-4266-9abc-08737da4dd41)

### Task 2. Find files containing specific strings

 1. Navigate to the /home/analyst/reports/users directory.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/b95e478c-d4da-46ad-bd05-e95228c80ffd)

  
 2. Using the pipe character (|), pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/f2795888-276e-4459-9790-ae1a02b800ca)

 3. List the files that contain the word access in their names.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/7d650b4c-1e91-4b17-9fb5-58298393f063)

### Task 3. Search more file contents

 1. Display the files in the /home/analyst/reports/users directory.
 
 ![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/d0256ff3-07aa-4961-9fac-09d96dd9a046)

 
 2. Search the Q2_deleted_users.txt file for the username jhill.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/3f92d319-8f1e-4385-8dd8-4940561cfc03)

 3. Search the Q4_added_users.txt file to list the users who were added to the Human Resources department.

![image](https://github.com/roulthegr8/Filter-with-grep/assets/90126847/b0c5d1aa-a753-4ac1-be5b-4a57e92e53d8)

