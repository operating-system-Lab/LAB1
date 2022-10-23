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


### What is a Process in an Operating System?
A process is essentially running software. The execution of any process must occur in a specific order. A process refers to an entity that helps in representing the fundamental unit of work that must be implemented in any system.

In other words, we write the computer programs in the form of a text file, thus when we run them, these turn into processes that complete all of the duties specified in the program.

A program can be segregated into four pieces when put into memory to become a process: stack, heap, text, and data. The diagram below depicts a simplified representation of a process in the main memory.

### Components of a Process
It is divided into the following four sections: <br />

 ![Components of a Process](https://cdn1.byjus.com/wp-content/uploads/2022/06/process-in-operating-system.png)

1. **Stack**
Temporary data like method or function parameters, return address, and local variables are stored in the process stack.

2. **Heap**
This is the memory that is dynamically allocated to a process during its execution.

3. **Text**
This comprises the contents present in the processor’s registers as well as the current activity reflected by the value of the program counter.

4.**Data**
The global as well as static variables are included in this section.

5. **Process Life Cycle**
When a process runs, it goes through many states. Distinct operating systems have different stages, and the names of these states are not standardised. In general, a process can be in one of the five states listed below at any given time.

6. **Start**
When a process is started/created first, it is in this state.

 7. **Ready**
Here, the process is waiting for a processor to be assigned to it. Ready processes are waiting for the operating system to assign them a processor so that they can run. The process may enter this state after starting or while running, but the scheduler may interrupt it to assign the CPU to another process.

8. **Running**
When the OS scheduler assigns a processor to a process, the process state gets set to running, and the processor executes the process instructions.

9. **Waiting**
If a process needs to wait for any resource, such as for user input or for a file to become available, it enters the waiting state.

10.**Terminated or Exit**
The process is relocated to the terminated state, where it waits for removal from the main memory once it has completed its execution or been terminated by the operating system.
 ![Terminated or Exit](https://cdn1.byjus.com/wp-content/uploads/2022/06/process-in-operating-system1.png)

11. **Process Control Block (PCB)**
Every process has a process control block, which is a data structure managed by the operating system. An integer process ID (or PID) is used to identify the PCB. As shown below, PCB stores all of the information required to maintain track of a process.

12. **Process state**
The process’s present state, such as whether it’s ready, waiting, running, or whatever.

13. **Process privileges**
This is required in order to grant or deny access to system resources.

14. **Process ID**
Each process in the OS has its own unique identifier.

15. **Pointer**
It refers to a pointer that points to the parent process.

16. **Program counter**
The program counter refers to a pointer that points to the address of the process’s next instruction.

17. **CPU registers**
Processes must be stored in various CPU registers for execution in the running state.

18 .**CPU scheduling information**
Process priority and additional scheduling information are required for the process to be scheduled.

19. **Memory management information**
This includes information from the page table, memory limitations, and segment table, all of which are dependent on the amount of memory used by the OS.

20. **Accounting information**
This comprises CPU use for process execution, time constraints, and execution ID, among other things.

21. **IO status information**
This comprises CPU use for process execution, time constraints, and execution ID, among other things.
This section includes a list of the process’s I/O devices.

The PCB architecture is fully dependent on the operating system, and different operating systems may include different information. A simplified diagram of a PCB is shown below.

 ![IO status information](https://cdn1.byjus.com/wp-content/uploads/2022/06/process-in-operating-system2.png)
 <br />

 The PCB is kept for the duration of a procedure and then removed once the process is finished.

 ### The Different Process States

The operating system’s processes can be in one of the following states: <br />

1. **NEW** : The creation of the process.
2. **READY** : The waiting for the process that is to be assigned to any processor.
3. **RUNNING** :Execution of the instructions.
4. **WAITING** : The waiting of the process for some event that is about to occur (like an I/O completion, a signal reception, etc.).
5. **TERMINATED** :A process has completed execution.

 ![state](https://cdn1.byjus.com/wp-content/uploads/2022/06/process-in-operating-system3.png)
 <br />

 ### Process vs Program
 A program is a piece of code that can be as simple as a single line or as complex as millions of lines. A computer program is usually developed in a programming language by a programmer. The process, on the other hand, is essentially a representation of the computer program that is now running. It has a comparatively shorter lifetime

### Process Scheduling
When there are several or more runnable processes, the operating system chooses which one to run first; this is known as process scheduling.

**A scheduler is a program** that uses a scheduling algorithm to make choices. The following are characteristics of a good scheduling algorithm:

1. For users, response time should be kept to a bare minimum.
2. The total number of jobs processed every hour should be as high as possible, implying that a good scheduling system should provide the highest possible throughput.
The CPU should be used to its full potential.
3. Each process should be given an equal amount of CPU time.


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



