# J.O.B-Training-Data Manipulation Commands Assignment

## You will now practice the data manipulation commands in Linux using the previously cloned repo that will track your work.

### Exercise 1 awk
In a terminal window practice the pattern-directed scanning and processing language program which is called awk. Awk is an advanced program and will take time to master.

1. In your terminal type the command ```man awk``` and read the documentation related to the command
2. Type the command ```cat phonebook.csv```
  * note that the file phonebook.csv prints on your screen 10 names and phone numbers
3. Type the command ```cat phonebook.csv | awk -F',' '{print $1" "$3}'``` 
  * note that the phonebook.csv file now prints only the first name and phone number on the screen
  * note that the -F denotes the field seperator and that we are using the comma to seperate each field in the file
4. Type the command ```cat phonebook.csv | awk -F'-' '{print $2 $3}'```
  * note that the field seperate is now the hyphen and that the second and third portions of the phone number now print on the screen
5. Type the command ```cat phonebook.csv | awk -F',' '{print $1" ""Middle"" "$2}'```
  * note that the use of quotes between the columns allows you to insert text and the result is firstname middle lastname

### Exercise 2 Nano
In a terminal window use the Nano command. This command is useful to edit files on your local disk.

1. In your terminal type the command ```man nano```
2. In your terminal type the command ```nano```
  * note that a window comes up with a blank screen at the top and a series of commands at the bottom
3. In the nano window type the words "this is a file created in nano"
  * on your keyboard press control O, which means save in nano
  * type in the file name nano.txt
  * press enter
  * press control X, which means to exit nano
4. In your terminal type the command ```ls -ltr```
  * note that you now have a file called nano.txt

### Exercise 3 Vim
In a terminal window practice the vim command. This command is useful edit files on your local disk and is more robust in options than nano. It can process find and replace operations in very large files very fast.

1. Type the command ```man vim``` and read the documentation
  * press the Q button to quit out of the manual
2. In your terminal type the command ```vim vim.txt```
3. In the vim window press the i button for insert and type the words "this is a file created in vim"
  * press the esc key
  * press the shift and : key
  * press the w and q keys
  * press enter
  * These steps have allowed you to create a new vim.txt file, insert text in the file, then write and quit the file.
4. In your terminal type the command ```ls -ltr```
  * note that you now have a file called vim.txt
5. Vim comes with its very own tutorial and provides lessons for you to practice and improve your use of vim. At the conclusion of this module you are encouraged to type ```vimtutor``` in a terminal and take the tutorial to improve your vim skills. 
  
### Exercise 4 Cut
In a terminal window practice the cut command.

1. Type the command ```man cut``` and read the documentation related to the manual for the change directory command
  * press the Q button to quit out of the manual
2. In your terminal type the command ```cat cutpractice.txt```
3. Now type ```cut -c2 cutpractice.txt```
  * note that the second character from each line is printed
4. Now ```cut -c1-3 cutpractice.txt```
  * note that the first 3 characters of each line are printed
5. Now type ```cut -c-8 cutpractice.txt```
  * note that the first 8 characters of each line are extracted from the begging of each line
6. Now type ```cut -c15- cutpractice.txt```
  * note that the last 15 characters of each line are extracted
7. Now type ```cut -c20- cutpractice.txt > cut.txt``` to log your work


## You have now completed the fourth online exercise for Linux commands. You will now be taken back to the Jump on Board website to begin the next section regarding network commands. Please return to the <a href="https://kevinhanson.github.io/J.O.B.-Jump-On-Board#network" target="_blank">Linux Commands Course Website</a> to continue to the next section.
