Shell is a command-line interface that allows you to interact with your computer's operating system by typing commands. One important feature of the shell is I/O redirection, which allows you to redirect the input and output of commands to and from files.

Commands like head, tail, find, wc, sort, uniq, grep, and tr are useful tools that you can use to perform various operations on files and directories. head and tail allow you to view the beginning and end of a file, respectively. find is used to locate files in a directory hierarchy. wc is used to count the number of lines, words, and characters in a file. sort is used to sort lines in a file. uniq is used to remove duplicate lines from a file. grep is used to search for a pattern in a file. tr is used to translate or delete characters from a file.

To redirect standard output to a file, you can use the > symbol followed by the name of the file. For example, ls > file.txt would redirect the output of the ls command to a file called file.txt.

To get standard input from a file instead of the keyboard, you can use the < symbol followed by the name of the file. For example, sort < file.txt would sort the contents of file.txt.

To send the output from one program to the input of another program, you can use the | symbol. For example, ls | grep file would list the files in the current directory and then pass the output to grep, which would search for lines containing the word "file".

You can also combine commands and filters with redirections. For example, cat file.txt | sort | uniq > output.txt would display the contents of file.txt, sort the lines, remove duplicate lines, and then redirect the output to a file called output.txt.
