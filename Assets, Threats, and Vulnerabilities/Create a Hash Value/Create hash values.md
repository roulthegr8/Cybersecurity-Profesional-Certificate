# Create hash values

## Introduction
In this lab, you'll create and evaluate the hash values for two files. You will use Linux commands to calculate the hash of two files and observe any differences in the hashes produced. Then, you'll determine if the files are the same, or different.

### What you’ll do
You have multiple tasks in this lab:
- List the contents of the home directory
- Compare the plain text of the two files presented for hashing
- Compute the sha256sum hash of the two separate files
- Compare the hashes provided to identify the differences
 
## Activity overview
As a security analyst, you’ll need to implement security controls to protect organizations against a range of threats.
That’s where hashing comes in. Previously, you learned that a hash function is an algorithm that produces a code that can’t be decrypted. Hash functions are used to uniquely identify the contents of a file so that you can check whether it has been modified. This code provides a unique identifier known as a hash value or digest.
For example, a malicious program may mimic an original program. If one code line is different from the original program, it produces a different hash value. Security teams can then identify the malicious program and work to mitigate the risk.Many tools are available to compare hashes for various scenarios. But for a security analyst it’s important to know how to manually compare hashes.

In this lab activity, we’ll create hash values for two files and use Linux commands to manually examine the differences.

## Scenario
In this scenario, we need to investigate whether two files are identical or different.

Here’s how you'll do this task: 
1. First, you’ll display the contents of two files and create hashes for each file.
2. Next, you’ll examine the hashes and compare them.

### Task 1. Generate hashes for files
The lab starts in your home directory, /home/analyst, as the current working directory. This directory contains two files file1.txt and file2.txt, which contain different data.

In this task, you need to display the contents of each of these files. You’ll then generate a hash value for each of these files and send the values to new files, which you’ll use to examine the differences in these values later.

1. Use the ls command to list the contents of the directory.
Two files, file1.txt and file2.txt, are listed.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/eb5ee2d6-cded-442f-9bd5-6eb694630809)

2. Use the cat command to display the contents of the file1.txt file:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/62250f43-1b5b-46fe-87db-57f89f5e84a2)

3. Use the cat command to display the contents of the file2.txt file:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/9967b2d0-d48a-4032-86a9-c3305cdf182a)

4. Review the output of the two file contents :

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/2b7e6c99-7b81-4d45-8259-05fab54a062e)
 
5. Use the sha256sum command to generate the hash of the file1.txt file:
![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/296b9933-fa90-4ad6-a785-11b98b4e840f)

You now need to follow the same step for the file2.txt file.
6. Use the sha256sum command to generate the hash of the file2.txt file:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/e0d19802-7a9a-49b8-8120-55b00141003d)

7. Review the generated hashes of the contents of the two files
   
![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/e3f436c3-3b26-40a8-bb56-7b86d5330c6c)

### Task 2. Compare hashes
In this task, you’ll write the hashes to two separate files and then compare them to find the difference.

1. Use the sha256sum command to generate the hash of the file1.txt file, and send the output to a new file called file1hash:
You now need to complete the same step for the file2.txt file.
2. Use the sha256sum command to generate the hash of the file2.txt file, and send the output to a new file called file2hash:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/1c5ea808-cb26-48a2-9b28-82e0d4d1bdd4)

Now, you should have two hashes written to separate files. The first hash was written to the file1hash file, and the second hash was written to the file2hash file.
You can manually display and compare the differences.

3. Use the cat command to display the hash values in the file1hash and file2hash files.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/70891e7d-fc8b-40bb-9f94-2fdb74c48935)

4. Inspect the output and note the difference in the hash values.
Note: Although the content in file1.txt and file2.txt previously appeared identical, the hashes written to the file1hash and file2hash files are completely different.
Now, you can use the cmp command to compare the two files byte by byte. If a difference is found, the command reports the byte and line number where the first difference is found.

5. Use the cmp command to highlight the differences in the file1hash and file2hash files:

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/f766b90a-6ef1-47bc-a6d1-3b43372996e7)

Review the output, which reports the first difference between the two files:

Note: The output of the cmp command indicates that the hashes differ at the first
