# Manage files with Linux commands

### Activity: Manage files with Linux commands
Activity overview
In this lab activity, you’ll use Linux commands to modify a directory structure and the files it contains.

You’ll also use the nano text editor to add text to a file.
You previously learned that directories help you organize subdirectories and files in Linux. As a security analyst, creating, removing, and editing directories and files are core tasks you’ll need to perform to help you to manage data.
When data is well organized, you can more easily detect issues and keep data safe.
With that in mind, you’re now ready to practice what you've learned.

### Scenario
In this scenario, you need to ensure that the /home/analyst directory is properly organized.
You have to make a few changes to the /home/analyst directory and the files it contains.
You also have to edit a file to record the changes or updates you make to the directory.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/c26597e6-852a-4a0f-850e-1edc96df6cf1)

## Task 1. Create a new directory

 1. First, you must create a dedicated subdirectory called logs, which will be used to store all future log files.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/d14c22fb-92ec-4fac-acfb-0c33631204fc)

 2. Create a new subdirectory called logs in the /home/analyst directory.
    List the contents of the /home/analyst directory to confirm that you’ve successfully created the new logs subdirectory.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/1b0d1c1c-be10-4d50-8889-b14f31482831)

## Task 2. Remove a directory

 1. Next, you must remove the temp directory, as you’ll no longer be placing items in it.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/8abda045-b7d5-415d-8128-789feaaf2b20)

 2. Remove the /home/analyst/temp directory.
    List the contents of the /home/analyst directory to confirm that you have removed the temp subdirectory.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/593d181c-27f7-44ad-8b6b-71ab580ad6e0)

## Task 3. Move a file

 1. The Q3patches.txt file contains notes taken on third-quarter patches and is now in the correct reporting format.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/71c6b604-aceb-427f-a6e3-b8c2839ee393)

 2. You must move the  Q3patches.txt file from the notes directory to the reports directory.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/22cfde17-0e3b-4492-92b8-902b80243654)


 3. Navigate to the /home/analyst/notes directory.
    Move the Q3patches.txt file from the /home/analyst/notes directory to the /home/analyst/reports directory.
    List the contents of the /home/analyst/reports directory to confirm that you have moved the file successfully.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/1fd3d854-adf7-462a-a2e6-fcfa84005802)

## Task 4. Remove a file

Next, you must delete an unused file called tempnotes.txt from the /home/analyst/notes directory.

 1. Remove the tempnotes.txt file from the /home/analyst/notes directory.
 
 ![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/9aafcbda-633f-4f02-bac2-49482c972aad)

 
 2. List the contents of the /home/analyst/notes directory to confirm that you’ve removed the file successfully.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/dcaaa0b1-bd64-4cab-8b6b-b0a0761be9cc)

## Task 5. Create a new file

 1. Now, you must create a file named tasks.txt in the /home/analyst/notes directory that you’ll use to document completed tasks.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/9d7c44ae-1948-488e-8fb1-d0f6044bc9cb)

 2. Use the touch command to create an empty file called tasks.txt in the /home/analyst/notes directory.
    List the contents of the /home/analyst/notes directory to confirm that you have created a new file.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/24ca338a-92d2-4784-97e2-046321ba4d57)

## Task 6. Edit a file

 1. Finally, you must use the nano text editor to edit the tasks.txt file and add a note describing the tasks you’ve completed.

 2. Using the nano text editor, open the task.txt file that is located in the /home/analyst/notes directory.

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/0fd56dda-8bb9-4434-a517-95b600d7edee)

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/c78a75b5-63ae-447b-a7c7-950e302ea134)

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/50ea2e55-a687-40d1-9b91-672a29c5a6cb)

Using "cat" command :

![image](https://github.com/roulthegr8/Manage-files-with-Linux-commands/assets/90126847/5ea43696-a5b1-4ba7-a361-de91f58acd49)
