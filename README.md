# LAB1
 ### What is Operating System?
 `Operating System lies in the category of system software. It basically manages all the resources of the computer. An operating system acts as an interface between the software and different parts of the computer or the computer hardware. The operating system is designed in such a way that it can manage the overall resources and operations of the computer. It is a fully integrated set of specialized programs that handle all the operations of the computer. It controls and monitors the execution of all other programs that reside in the computer, which also includes application programs and other system software of the computer. Examples of the operating system are Windows, Linux, Mac OS, etc`
 
 
 ![Diagram of the operating system](https://media.geeksforgeeks.org/wp-content/uploads/20210607180134/operatingsys-300x225.jpg)
 
 ### Objectives of the operating system:

1. Convenient to use: One of the objectives is to make the computer system more convenient to use in an efficient manner.
2. User Friendly: To make the computer system more interactive with a more convenient interface for the users.
3. To provide easy access to users for using resources by acting as an intermediary between the hardware and its users.
4. For managing the resources of a computer.
5. Controls and Monitoring: By keeping the track of who is using which resource, granting resource requests, and mediating conflicting requests from different programs and users.
6. Providing efficient and fair sharing of resources between the users and programs.

### Characteristics:

1. **Device Management:** The operating system keeps track of all the devices. So, it is also called the Input / Output controller that decides which process gets the device, when, and for how much time.<br />
2. **File Management:** It allocates and de-allocates the resources and also decides who gets the resource.<br />
3. **Job Accounting:** It keeps the track of time and resources used by various jobs or users.<br />
Error-detecting Aids: It contains methods that include the production of dumps, traces, error messages, and other debugging and error-detecting methods.<br />
4. **Memory Management:** It keeps track of the primary memory, like what part of it is in use by whom, or what part is not in use, etc. and It also allocates the memory when a process or program requests it.<br />
5. **Processor Management:** It allocates the processor to a process and then de-allocates the processor when it is no longer required or the job is done.
Control on System Performance: It records the delays between the request for a service and from the system.<br />
6. **Security:** It prevents unauthorized access to programs and data by means of passwords or some kind of protection technique.<br />

### Types of the operating system:

1. **Batch Operating System:** This type of operating system does not interact with the computer directly. There is an operator which takes similar jobs having the same requirements and groups them into batches.<br />
2. **Time-sharing operating System:** This type of operating system allows many users to share computer resources. (Max utilization of the resources).<br />
3. **Distributed operating System:** This type of operating system manages a group of different computers and makes appear to be a single computer.<br />
4. **Network operating system:** This type of operating system running on a server and provides the capability to manage data, users, groups, security, applications, and other networking functions.<br />
5. **Real-time operating system:** This type of operating system serves real time system and the time interval required to process and respond to inputs is very small. <br / >

### Cmder - The best way to run Linux, Shell, Bash commands and scripts in windows 
  **DownLoad** [Cmder](https://cmder.app/).
 
# Hands on Unix Commands.



### Theory/Description:
- 	**pwd COMMAND:**
1.  pwd - Print Working Directory. pwd command prints the full filename of the current working directory.
`SYNTAX:
 pwd [options]`

-	**cd COMMAND:**
1. cd command is used to change the directory. SYNTAX:
2. cd [directory | ~ | ./ | ../ | - ]

-	**ls COMMAND:**
1. ls command lists the files and directories under current working directory. SYNTAX:
2. ls [OPTIONS]... [FILE] OPTIONS:

 - -l	Lists all the files, directories and their mode, Number of links, owner of the file, file size, Modified date and time and filename.
- -t	Lists in order of last modification time.
- -a	Lists all entries including hidden files.
- -d	Lists directory files instead of contents.
- -p	Puts slash at the end of each directories.
- -u	List in order of last access time.
- -i	Display inode information.

-	**rm COMMAND:**
1. rm linux command is used to remove/delete the file from the directory. SYNTAX:
2. rm [options..] [file | directory]
OPTIONS:
3. -f	Remove all files in a directory without prompting the user.
4. -i	Interactive. With this option, rm prompts for confirmation before removing any files.

- **mv COMMAND:**
1. mv command which is short for move. It is used to move/rename file from one directory to another. mv command is different from cp command as it completely removes the file from the source and moves to the directory specified, where cp command just copies the content from one file to another. SYNTAX:
2. mv [-f] [-i] oldname newname OPTIONS:
3. -f	This will not prompt before overwriting (equivalent to -- reply=yes). mv -f will move the file(s) without prompting even if it is writing over an existing target.
4. -i	Prompts before overwriting another file.


-	**cat COMMAND:**
cat linux command concatenates files and print it on the standard output.
> SYNTAX:
The Syntax is
`cat [OPTIONS] [FILE]...`

- **OPTIONS:**
- -A Show all.
- -b	Omits line numbers for blank space in the output.
- -E	Displays a $ (dollar sign) at the end of each line.
- -n	Line numbers for all the output lines.


⦁	**cmp COMMAND:**
cmp linux command compares two files and tells you which line numbers are different.
SYNTAX:
cmp [options..] file1 file2 OPTIONS:
⦁	c	Output differing bytes as characters.
⦁	l	Print the byte number (decimal) and the differing byte values (octal) for each difference.
⦁	s	Prints nothing for differing files, return exit status only.

⦁	**cp COMMAND:**
cp command copy files from one location to another. If the destination is an existing file, then the file is overwritten; if the destination is an existing directory, the file is copied into the directory (the directory is not overwritten).
SYNTAX:
cp [OPTIONS]... SOURCE DEST

⦁	**echo COMMAND:**
echo command prints the given input string to standard output. SYNTAX:
echo [options..] [string]

⦁	**mkdir COMMAND:**
mkdir command is used to create one or more directories. SYNTAX:
mkdir [options] directories
OPTIONS:
-m	Set the access mode for the new directories.
-p	Create intervening parent directories if they don't exist.
-v	Print help message for each directory created.

⦁	**paste COMMAND:**
paste command is used to paste the content from one file to another file. It is also used to set column format for each line.
SYNTAX:
paste [options] OPTIONS:
-s	Paste one file at a time instead of in parallel.
-d	Reuse characters from LIST instead of TABs .

⦁	**rmdir COMMAND:**
rmdir command is used to delete/remove a directory and its subdirectories. SYNTAX:
rmdir [options..] Directory
OPTIONS:
-p	Allow users to remove the directory dir name and its parent directories which become empty.


⦁	**head COMMAND:**
It is the complementary of Tail command. The head command, as the name implies, print the top N number of data of the given input. By default it prints the first 10 lines of the specified files. If more than one file name is provided then data from each file is precedes by its file name.
SYNTAX:
head [OPTION]… [FILE]…

⦁	**tail COMMAND:**
It is the complementary of head command.The tail command, as the name implies, print the last N number of data of the given input. By default it prints the last 10 lines of the specified files. If more than one file name is provided then data from each file is precedes by its file name.
SYNTAX:
tail [OPTION]… [FILE]…

⦁	**date COMMAND:**
date command is used to display the system date and time. date command is also used to set date and time of the system. By default the date command displays the date in the time zone on which unix/linux operating system is configured.You must be the super-user (root) to change the date and time.
SYNTAX:
date [OPTION]… [+FORMAT]




#### Conclusion :
  ##### QUESTIONS :

1. ⦁	What is the description for Kernel?
2. ⦁	What are the main features of UNIX?
3. ⦁	What is called Shell?
4. ⦁	What is the general format of UNIX command syntax?
5. ⦁	Describe the usage and functionality of the command “rm” in UNIX?
6. ⦁	Describe the term directory in UNIX?
7. ⦁	What is the command to find today’s date?
8. ⦁	What is the UNIX command to make a new directory?
9. ⦁	What is the purpose of “echo” command?
10. ⦁	What do you understand by UNIX shell?



