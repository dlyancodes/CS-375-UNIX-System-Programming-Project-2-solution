# CS-375-UNIX-System-Programming-Project-2-solution

Download Here: [CS 375 – UNIX System Programming Project 2 solution](https://jarviscodinghub.com/assignment/cs-375-unix-system-programming-project-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (5 points) There is a limit to the size of the per-process file table, i.e., there is a maximum number of
files that any single process may have open. Determine this limit by writing a C/C++ program
count-opens (note that the name of the program has a hyphen, not an underscore) that repeatedly
calls the open routine, without accompanying calls to close, until a call to open fails. It is suggest
having the program repeatedly open itself (argv[0]), since that file should always exist. Answer
the following question in a comment at the beginning of the program file: How many file
descriptors may a process have open? (Don’t forget the three that are opened automatically for the
process by the OS.)
2. (10 points) Write a C/C++ program lsl that outputs the same information (and in the same format)
as the “ls -l” command. It should take either zero or one directory names as arguments. If no
argument is given the program should do a long directory listing on the current directory.
3. (10 points) Write a C/C++ program kitten that is a replacement for the cat program. Only the -E,
-n, and -s options are to be supported. Any other command arguments should be treated as input
file names. The program must use getopt() to process the command line options. If no input file
names are supplied as arguments on the command line, then the program should read from standard
input.
4. (5 points) Provide a makefile named Makefile that will make all three programs for this
assignment as the default target (typically called all). Each program must be a separate target.
What to submit
Create a tarfile or zipfile containing your three program source files and makefile.
Submit your archive using the submission system (https://submission.evansville.edu). The grading script
will only make the project and check that executables named count-opens, lsl, and kitten are
produced. It will not run anything.

