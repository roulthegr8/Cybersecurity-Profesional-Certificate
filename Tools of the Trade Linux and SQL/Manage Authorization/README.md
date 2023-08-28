# ManageAuthorization

## Activity: Manage authorization

## Introduction
In this lab, you’ll learn how to examine and manage file permissions. These skills can be used when configuring user authorization. You’ll use Linux commands in the Bash shell to complete this lab.

What you’ll do
You have multiple tasks in this lab: 

- Check permissions for files in a directory
- Check for incorrect file permissions and change permissions as needed
- Remove unauthorized access to a directory

## Scenario
In this scenario, you must examine and manage the permissions on the files in the /home/researcher2/projects directory for the researcher2 user.
The researcher2 user is part of the research_team group.
You must check the permissions for all files in the directory, including any hidden files, to make sure that permissions align with the authorization that should be given. When it doesn't, you must change the permissions.

Here’s how you’ll do this task: 
1. First, you’ll check the user and group permissions for all files in the projects directory.
2. Next, you’ll check whether any files have incorrect permissions and change the permissions as needed.
3. Finally, you’ll check the permissions of the /home/researcher2/projects/drafts directory and modify these permissions to remove any unauthorized access.

### Task 1. Check file and directory details
In this task, you must explore the permissions of the projects directory and the files it contains. The lab starts with /home/researcher2 as the current working directory. This is because you're changing permissions for files and directories belonging to the researcher2 user.

 1. Navigate to the projects directory.

 2. List the contents and permissions of the projects directory.

 ![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/3b646e63-c7b0-4a41-96c6-ab79c363a81d)

 3. Check whether any hidden files exist in the projects directory.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/22919d39-4aef-4fe3-af77-499afac7f169)

### Task 2. Change file permissions

In this task, you must determine whether any files have incorrect permissions and then change the permissions as needed. This action will remove unauthorized access and strengthen security on the system.
None of the files should allow the other users to write to files.

1. Check whether any files in the projects directory have write permissions for the owner type of other.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/36f73aed-75d3-4956-ac5f-d056fbabf014)

2. Change the permissions of the file identified in the previous step so that the owner type of other doesn’t have write permissions.

chmod o-w project_k.txt

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/84291199-71ff-4a2f-9e0b-cc3f83795952)

3. The file project_m.txt is a restricted file and should not be readable or writable by the group or other; only the user should have these permissions on this file. List the contents and permissions of the current directory and check if the group has read or write permissions.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/550d89f3-166c-4466-a7bb-8e4a09689396)

4. Use the chmod command to change permissions of the project_m.txt file so that the group doesn’t have read or write permissions.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/2deb6752-ad79-489e-94e0-82e657e81c8c)

### Task 3. Change file permissions on a hidden file

In this task, you must determine if a hidden file has incorrect permissions and then change the permissions as needed. This action will further remove unauthorized access and strengthen security on the system.
The file .project_x.txt is a hidden file that has been archived and should not be written to by anyone. (The user and group should still be able to read this file.)

1. Check the permissions of the hidden file .project_x.txt and answer the question that follows.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/ef363a6f-ace7-4ec3-a02e-871b4e46c015)

2. Change the permissions of the file .project_x.txt so that both the user and the group can read, but not write to, the file.

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/aa9ca04f-3bf5-4f69-ab41-00631acc0a0b)

Task 4. Change directory permissions

In this task, you must change the permissions of a directory. First, you’ll check the group permissions of the /home/researcher2/projects/drafts directory and then modify the permissions as required. (You should be in the projects directory while managing the permissions of its subdirectory drafts.)

Only the researcher2 user should be allowed to access the drafts directory and its contents. (This means that only researcher2 should have execute privileges.)

![image](https://github.com/roulthegr8/ManageAuthorization/assets/90126847/05c341f1-2f42-4db0-9155-9920b6d301fb)











