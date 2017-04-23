# J.O.B-Training-File Handling Commands Assignment

## You will now practice the file handling commands in Linux using the previously cloned repo that will track your work.

### Exercise 1 Touch
In a terminal window practice the touch command which is called touch.

1. In your terminal type the command ```man touch``` and read the documentation related to the command
2. Type the command ```touch file.txt``` 
	* Type the command ```ls -ltr``` and note that you now have a file called file.txt created that is 0 bytes in size
3. Type the command ```echo 'this is line one' > file.txt```
	* Type the command cat file.txt and note that the information this is line one is now added to file.txt

### Exercise 2 CP
In a terminal window use the copy command which is call cp. This command is copy files on your local disk.

1. In your terminal type the command ```man cp``` and read the documentation related to the command
2. In your terminal type the command ```cp file.txt file2.txt```
3. In your terminal type the command ```ls -ltr```
  * note that there is now a file2.txt file and that it is the same size as file.txt
4. In your terminal type the command ```cp file2.txt ~/Desktop```
5. Open a finder  window a see that file.txt is copied to your desktop

### Exercise 3 RM
In a terminal window practice the remove command which is called rm. This command is used to remove or delete files from local disk.

1. Type the command ```man rm``` and read the documentation related to the manual for the change directory command
  * press the Q button to quit out of the manual
2. In your terminal type the command ```touch removeme.txt```
3. In your terminal type the command ```ls -ltr```
  * note you have a file called removeme.txt
4. In your terminal type the command ```rm removeme.txt```
5. In your terminal type the command ```ls -ltr```
  * note that the file removeme.txt is gone now

### Exercise 4 MKDIR
In a terminal window practice the make directory command which is called mkdir.

1. Type the command ```man mkdir``` and read the documentation related to the manual for the change directory command
  * press the Q button to quit out of the manual
2. In your terminal type the command ```mkdir mydata```
3. In your terminal type the command ```ls -ltr```
  * note you have a directory called mydata

### Exercise 5 MV
In a terminal window practice the move command which is called mv.

1. Type the command ```man mv``` and read the documentation related to the manual for the move command
  * press the Q button to quit out of the manual
2. In your terminal type the command ```mv ~/Desktop/file2.txt file3.txt```
  * note the file2.txt file you copied to your desktop is now moved to your local directory and is called file3.txt now


## You have now completed the third online exercise for Linux commands. You will now be taken back to the Jump on Board website to be introduced to the next section regarding data manipulation commands.Please return to the <a href="https://kevinhanson.github.io/J.O.B.-Jump-On-Board#data" target="_blank">Linux Commands Course Website</a> to continue to the next section.
