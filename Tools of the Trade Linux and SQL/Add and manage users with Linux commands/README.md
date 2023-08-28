# Add and manage users with Linux commands

Activity: Add and manage users with Linux commands

## Introduction
In this lab, you’ll learn how to add users and manage user access in a system. These skills can be used when working with authentication technology. You’ll use Linux commands in the Bash shell to complete this lab.

- What you’ll do
  - You have multiple tasks in this lab:
  - Add a new employee
  - Change ownership of a file
  - Add the new employee to a new group
  - Delete the employee from the system
 
## Activity overview
Previously, you focused on authorization, the concept of granting access to specific resources in a system. Another important concept in security is authentication. Authentication is the process of a user proving that they are who they say they are in the system.

When managing this, security analysts need to ensure not all users get access to the system,new users (those who are new to the organization or a group) are added to the system, and
current users who change groups or leave the organization are deleted from the system. 

In this lab activity, you’ll use the useradd, usermod, userdel, and chown commands to manage user access in the Linux Bash shell.

## Scenario
In this scenario, a new employee with the username researcher9 joins an organization. You have to add them to the system and continue to manage their access during their time with the organization.

Here’s how you’ll do this task: First, you’ll add a new employee to the system and then to their primary group. Second, you’ll make this employee the owner of a file related to a particular project. Third, you’ll add the new employee to a supplementary group. Finally, you’ll delete the employee from the system.

### Task 1. Add a new user
A new employee has joined the Research department. In this task, you must add them to the system. The username assigned to them is researcher9.

1. Write a command to add a user called researcher9 to the system.

![image](https://github.com/roulthegr8/Add-and-manage-users-with-Linux-commands/assets/90126847/d8ef9e36-e79b-45a2-b309-42854f580b59)

   Next, you need to add the new user to the research_team group.

3. Use the usermod command and -g option to add researcher9 to the research_team group as their primary group.

![image](https://github.com/roulthegr8/Add-and-manage-users-with-Linux-commands/assets/90126847/948d6906-3cfe-4a99-8ecd-3f04c7a38860)

### Task 2. Assign file ownership
The new employee, researcher9, will take responsibility for project_r. In this task, you must make them the owner of the project_r.txt file.
The project_r.txt file is located in the /home/researcher2/projects directory, and owned by the researcher2 user.

Use the chown command to make researcher9 the owner of /home/researcher2/projects/project_r.txt.

![image](https://github.com/roulthegr8/Add-and-manage-users-with-Linux-commands/assets/90126847/9d4087b3-100e-4c0e-8536-4b7d583e26e2)

### Task 3. Add the user to a secondary group
A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.
In this task, you must add researcher9 to a secondary group (sales_team). Their primary group is still research_team.

Use the usermod command with the -a and -G options to add researcher9 to the sales_team group as a secondary group.

![image](https://github.com/roulthegr8/Add-and-manage-users-with-Linux-commands/assets/90126847/c7db1a9e-951b-4eed-8d1e-a9a22c2ce57c)

### Task 4. Delete a user

A year later, researcher9, decided to leave the company. In this task, you must remove them from the system.

![image](https://github.com/roulthegr8/Add-and-manage-users-with-Linux-commands/assets/90126847/25285669-044a-4025-b1a1-4b2b52f4faca)




