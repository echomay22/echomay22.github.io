---
layout: default
---

Command line tools for linguists is a course at the University of Helsinki that introduces students to command line as a tool to process linguistic data. This course focuses on navigating file systems, processing text and using regex.

Here are what the course went over week to week:

## Module 1

In module 1, we first learned how to list the current directory to know in which directory we are working in with **pwd**
We then learned now to change directories with **cd** . After that we also focused on downloading files from the internet with **wget** . If you have a text file, we learned that you can view it using **less**.
We learned how to create files using **nano** or **touch** and directories using **mkdir** . Removing them as well with **rm** and if its an empty directory **rmdir** . If its not empty then **rm -r**.
Copying files is easy with **cp** and renaming and moving them with **mv**.
During this module we visited our root directories of our systems. We also learned now to find out and change read and write permissions for a file.


## Module 2

In this second section, we learned about ASCII, Latin-1 and UTF-8 encodings and how to convert a text file from Latin -1 to UTF-8. We also learned now to convert Windows text files to UNIX format with **docs2unix**.
In this module, we were learned how to print the first and last lines of a text file with **head** and **tail**.
We were able to count the number of lines in a text file with **wc -l**
We learned how to change from uppercase to lowercase with **tr 'A-Z' 'a-z'**.
Sorting lines with **sort** and removing duplicate lines from a sorted file with **uniq**.
Search for patterns in files is made easy with **grep** or **egrep**. And of course with grep came learning to read and write with regex.
We learned how to save the output of a command directly to a file using **>**
To use all of these commands in sync we had to using piping **|** and we also learned how to use **sed** to delete lines and replace patterns.

Later in this section we learned how to make a frequency list out of words within a text file.
To do this, we had to also learn how to convert text into one word per line format and also learned how to do one sentence per line.

## Module 3

In this section we were introduced to writing simple scripts. We learned about making loops and making if statements within scripts.
We learned that we can see the values of existing environment variables by using **echo** and that you can change their value and define new ones using **export**.
We also learned that the .bashrc / .bash_profile files can be modified to create a more pleasant working environment with shortcuts and other personalisations. 
This week we learned that you can give commands as the root user by using **sudo**.
We learned that you can install software by using **apt-get** or **brew** and that python packages can be installed by using **pip**.
We also learned how to make and run our own virtual environments.


## Section 4
This week we learned how to kill a process.
We learned how to make a remote connection to a CSC server and to copy files to and from the server.
Next, we learned about version control and why it is important. After this, we learned and started working in Github. Within Github we learned how to clone repositories, create our own and start our own project by forking someone's template.


## Final Project

This is the final project!!! 

For this project we needed to be able to navigate and write markdown files and create links to display on our website.

Enjoy!!!
