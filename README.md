# J.O.B-Training-Linux File Commands Assignment

## This is the first online assignment for the Linux commands training module and in this assignment you will clone this repository to your local computer by doing the following:
1. click the fork button
2. Select your GitHub account as the desitnation to fork the repository
3. Click the link to your newly forked repository
4. Click the clone or download button
5. Click the copy to clipboard button
6. Open a terminal window
7. Type git clone and then press command V to paste the clipboard url in your terminal
8. Press enter

## You will now practice the file commands in Linux using the newly cloned repo that will track your work.
Before you begin, set your current repository to a variable we can use later by typing ``` repodir=`pwd` ```
Note: the symbol used in the above command is the backtick and not the single quote. The backtick is next to the number 1 on your keyboard.

### Exercise 1 Manual
The ```man``` command is used to display the manual for any Linux command. If you forget how to use a command in Linux you can simply type ```man``` and then the command you want to read about. For example you can type ```man ls``` to display the manual that describes the function and options for the list directory content command. You will use the man command in the further exercises of this module.

### Exercise 2 Present Working Directory
In a terminal window practice the present working directory command which is call pwd.

1. In your terminal type the command pwd
	* note that the terminal displays the current directory that you are working in
2. Document your current directory by typing the command ```pwd > pwd.txt```
3. Change directory to the root of your file system by typing ```cd /``` and then type ```pwd```
4. Change directory to the users directory by typing ```cd /users``` and then type ```pwd```
5. Type the command ```cd $repodir``` to return to your exercise directory

### Exercise 3 Change Directory
In a terminal window practice the change directory command which is called cd. 

1. Change directory to the root of your file system by typing ```cd /```
2. Change directory to your Linux home drive by typing ```cd ~```
3. Type the command ```cd $repodir``` to return to your exercise directory
4. Verify that you are in your exercise directory by typing ```pwd >> pwd.txt```

### Exercise 4 List Directory Content
In a terminal window practice the list directory content command which is called ls.

1. Type the command ```man ls``` and read the manual for the command
  * pay particular attention to the options -l -t -r -a -h
2. List the current contents of the directory you are located in by typing ```ls```
3. List the current contents of the directory you are located by file creation date by typing ```ls -ltr```
  * note that the files in your current directory are listed by date
4. List the current contents of the directory you are located in by listing hidden files by typing ```ls -lah```
  * note that the you now see more directories such as .git and .DS_Store
5. List hidden files in the current directory by creation date by typing ```ls -latr```
  * note that you see all files plus hidden files sorted by last modified date
6. Type the command ```ls -latr > ls.txt``` to log your work to the file ls.txt for later review

### Exercise 5 Concatenate
In a terminal window practice the concatenate command which is called cat. Concatenate can display any human readable file such as a text file, a comma serperated values file or script.

1. Type the command ```man cat``` and read the manual for the command
2. Display the content of the pwd.txt file to your screen by typing ```cat pwd.txt```
  * see that the cat file displays on your screen the pwd.txt file you created in the present working directory exercise
3. Type ```cd /``` and then type ```cat users```
  * note that you receive an error when trying to concatenate users because it is a directory and not a file 
4. Type the command ```cd $repodir``` to return to your exercise directory
5. Type ```echo 'This is a test file' > test.txt``` and then type ```cat test.txt```

### Exercise 6 Execute a Command as another User
In a terminal window practice executing commands as another user by typing sudo. Sudo is a very powerful command that allows you to execute programs on a Linux system that are restricted to specific account with higher elevated rights.
1. Type the command ```man sudo``` and read the manual for the command
2. Type the command ```sudo su -``` and type in your password
  * note that your terminal now reads root because you have just switched to the root user account. Every command you type is executed as the root user and can be harmful if you are not careful
3. Type the command ```exit``` to return to your regular user account

### Exercise 7 General Regular Expression Parser
In a terminal window practice the general regular expression parser command by typing grep. Grep is a very powerful command that allows you to print lines from a file that match information you are searching for in human readable files. This command is often used to search for and identify patterns in a file or count lines in a file. The uses of the grep command are extensive.

1. Type the command ```man grep``` and read the manual for the command
2. Type the command ```grep we gettysburg-address.txt```
  * note that your terminal returns every line in the file that includes the word we
3. Now type the command ```grep -i we gettysburg-address.txt``` and press enter
  * note that your terminal returns every line in the file that inclues the word we and We because the -i option turns on case insensitivity for grep
4. Now type the command ```grep -in we gettysburg-address.txt``` and press enter
  * note that the line number on which the word we is listed before each line returned
5) Now type the command ```grep -ic we gettysburg-address.txt``` and press enter
  * note that the number of times the word we or We is in the Gettysburg Address is counted
6. Now type the command ```grep -in 'it' * > grep.txt``` and press enter
  * note that grep has searched every file in the current directory for the word it and returned output showing the file and line number it found it on

## You have now completed the first online exercise for Linux commands. You will now be taken back to the Jump on Board website to begin the next section regarding system commands. Please return to the <a href="https://kevinhanson.github.io/J.O.B.-Jump-On-Board#system" target="_blank">Linux Commands Course Website</a> to continue to the next section.
