# Rshell
This is a mimic of the bash shell. Forking was used to execute different commands and arguments. 
Composite Pattern was utilized to organize different classes and link them together. 
Several system calls were used and referenced from the linux page for making this program work. 

# Details
Each command and argument were "tokenized" with the Token class to separate them into two chunks. 
The boost library was used to separate the user-input string into a vector.
These were then parsed based on connectors and redirectors. 
Finally, a tree was built for the executable to execute the different commands. 

# Bugs
Error message for using || connectors prints out twice.
