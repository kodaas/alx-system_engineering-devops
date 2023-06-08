# alx-system_engineering-devops 

## 0x00-shell_basics

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.


## 0x01-shell_permissions

* What do the commands ``chmod``, ``sudo``, ``su``, ``chown``, ``chgrp`` do
* Linux file permissions
* How to represent each of the three sets of permissions (owner, group, and other) as a single digit
* How to change permissions, owner and group of a file
* Why can’t a normal user ``chown`` a file
* How to run a command with root privileges
* How to change user ID or become superuser

## 0x02. Shell, I/O Redirections and filters

### Shell, I/O Redirection
- What do the commands head, tail, find, wc, sort, uniq, grep, tr do
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections
### Special Characters
- What are special characters
- Understand what do the white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde and how and when to use them
### Other Man Pages
- How to display a line of text
- How to concatenate files and print on the standard output
- How to reverse a string
- How to remove sections from each line of files
- What is the /etc/passwd file and what is its format
- What is the /etc/shadow file and what is its format


## 0x03-shell_variables_expansions

### General
- What happens when you type $ ls -l *.txt
### Shell Initialization Files
- What are the /etc/profile file and the /etc/profile.d directory
- What is the ~/.bashrc file
### Variables
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter $??
### Expansions
- What is expansion and how to use them
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with $() and backticks
### Shell Arithmetic
- How to perform arithmetic operations with the shell
### The alias Command
- How to create an alias
- How to list aliases
- How to temporarily disable an alias
### Other help pages
- How to execute commands from a file in the current shell
