# Activity: Decrypt an encrypted message


## Introduction
In this lab, you'll complete a series of tasks to obtain instructions for decrypting an encrypted file. Encryption of data in use, at rest, and in transit is critical to security functions. You'lll use the Linux skills you have learned to uncover the clues needed to decode a classical cipher, restore a file, and reveal a hidden message.

### What you’ll do
- You have multiple tasks in this lab:

 - List the contents of a directory
 - Read the contents of files
 - Use Linux commands to revert a classical cipher back to plaintext
 - Decrypt an encrypted file and restore the file to its original state
 
## Activity overview
Previously, you learned about cryptography and how encryption and decryption can be used to secure information online. You were also introduced to the Caesar cipher, one of the earliest cryptographic algorithms used to protect people’s privacy.

As a security analyst, it’s important that you understand the role of encryption to secure data online and that you’re familiar with the right security controls to do so.

In this lab activity, you’ll be guided through some basic cryptographic activities using Linux commands to decrypt files and reveal hidden messages.

## Scenario
In this scenario, all of the files in your home directory have been encrypted. You’ll need to use Linux commands to break the Caesar cipher and decrypt the files so that you can read the hidden messages they contain.

Here’s how you’ll do this task: 
 1. First, you’ll explore the contents of the home directory and read the contents of a file. 
 2. Next, you’ll find a hidden file and decrypt the Caesar cipher it contains.
 3. Finally, you’ll decrypt the encrypted data file to recover your data and reveal the hidden message.

## Task 1. Read the contents of a file
The lab starts in your home directory, /home/analyst, as the current working directory.

In this task, you need to explore the contents of your home directory and read the contents of a file to get further instructions.

Use the ls command to list the files in the current working directory.
Two files, Q1.encrypted and README.txt, and a subdirectory, caesar, are listed:

Q1.encrypted  README.txt caesar
The README.txt file contains an important message with instructions you need to follow.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/c5dd9249-159a-409b-b5d2-8cfafb2b284d)

Use the cat command to list the contents of the README.txt file.
The message in the README.txt file advises that the caesar subdirectory contains a hidden file.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/79ba03aa-9206-44dd-9776-81603f448308)

In the next task, you’ll need to find the hidden file and solve the Caesar cipher that protects it. The file contains instructions on how to recover your data.

## Task 2. Find a hidden file
In this task, you need to find a hidden file in your home directory and decrypt the Caesar cipher it contains. This task will enable you to complete the next task.

1. First, use the cd command to change to the caesar subdirectory of your home directory:

cd caesar

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/8d80b277-13ba-4151-a764-be441baa318b)

2. Use the ls -a command to list all files, including hidden files, in your home directory.

This will display the following output:

.  ..  .leftShift3

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/838d5ca0-ae20-4729-8dd0-f6ba2ad7f385)

Hidden files in Linux can be identified by their name starting with a period (.).

3. Use the cat command to list the contents of the .leftShift3 file.
The message in the .leftShift3 file appears to be scrambled. This is because the data has been encrypted using a Caesar cipher. This cipher can be solved by shifting each alphabet character to the left or right by a fixed number of spaces. In this example, the shift is three letters to the left. Thus "d" stands for "a", and "e" stands for "b".

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/028df26e-6233-4240-a6df-77e54735287c)

4. You can decrypt the Caesar cipher in the .leftshift3 file by using the following command:

cat .leftShift3 | tr "d-za-cD-ZA-C" "a-zA-Z"

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/f8973b01-0022-4642-b82a-409247716579)

5. Now, return to your home directory before completing the next task:

cd ~

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/87f8667f-1a5d-4cb3-bf74-efe3ba0eb714)

## Task 3. Decrypt a file
Now that you have solved the Caesar cipher, in this task you need to use the command revealed in .leftshift3 to decrypt a file and recover your data so you can read the message it contains.

![image](https://github.com/roulthegr8/Cybersecurity-Profesional-Certificate/assets/90126847/3985f527-0043-4ab0-a6a2-ed691d37c17b)



