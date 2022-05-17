 **List of Commands**
* date- Display date as mm/dd/yy.date command is used to display the system date and time. date command is also used to set date and time of the system. syntax date OPTIONS +FMT TIME
* uname-uname is a computer program in Unix and Unix-like computer operating systems that prints the name, version and other details about the current machine and the operating system running on it. syntax uname -amnrspv
* du-short for disk usage, is used to estimate file space usage. syntax du -aHLdclsxhmk FILE...
* free-Display amount of free and used memory in the system syntax free -b|-k|-m -o -s delay -t -l -V
* echo- linux is used to display line of text/string that are passed as an argument.syntax echo -n string 
* apt-is a command-line utility for installing, updating, removing, and otherwise managing deb packages on Ubuntu, Debian, and related Linux distributions. syntax apt get update
* pwd- pwd stands for Print Working Directory. syntax pwd OPTION
* cd-also known as chdir (change directory), is a command-line shell command used to change the current working directory Syntax: $ cd [directory] 
* ls-ls is a command to list computer files in Unix and Unix-like operating systems.syntax ls -1Aac file
* tree-tree is a recursive directory listing command or program that produces a depth-indented listing of files. syntax TREE (Display Directory)
* man- used to display the user manual of any command that we can run on the terminal syntax man -C file
* mkdir-allows the user to create directories (also referred to as folders in some operating systems ). syntax mkdir -p -m mode directory 
* touch-which is used to create, change and modify timestamps of a file.syntax touch -c -d DATE FILE
* rm-rm command is used to remove objects such as files, directories, symbolic links and so on from the file system syntax rm -dfiPRr file 
* cp- is used to copy files or group of files or directory.syntax cp -fip -R -H|-L|-P SOURCE DEST
* mv is used to move one or more files or directories from one place to another in a file system like UNIX. Syntax: mv OPTION
* stat-Stat command gives information such as the size of the file  Syntax: stat -FLnq
* Wildcards (*,?,[])-are symbols or special characters that represent other characters. *
* Brace expansion- is a mechanism by which arbitrary strings may be generated.[]
* cat-is a standard Unix utility that reads files sequentially, writing them to standard output. syntax cat -benstuv file cat file1 file2 > file3 
* head-Unix-like operating systems used to display the beginning of a text file or piped data. Syntax: head OPTIONS FILE Example: head -n 500 foo
* tail-It is the complementary of head command.The tail command, as the name implies, print the last N number of data of the given input.syntax tail -f|-r -b number|-c number|-n number|-number file 
* cut- Cut is a command that allows you to "cut out" a selection of text or other data and save it to the clipboard.Syntax: cut -f list -s -d delim  example cut -d : -f 1,7 /etc/passwd
* tr-The tr command in UNIX is a command line utility for translating or deleting characters  tr A-Z a-z <mixed >lower
* paste- In order to use the Paste command, you must first use either the Copy or Cut command to save data to the clipboard.ctrl v
* wc-It is used to find out number of lines, word count : syntax wc OPTIONS FILE
* grep- grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern.Syntax: grep -HhrilLnq PATTERN FILE...
* output redirection-a rightward pointing angular bracket (>) that is used in shells to redirect standard output to a file, where it is written and saved, or to a device 
*Saving the output of a command- saves the contents of an open output document to a file
* vim or nano (basic stuff: open a file, close a file, edit a file)- explain the basic usage of the nano editor, including how to create and open a file, edit a file, save a file
* tar-stands for tape archive, is used to create Archive and extract the Archive files. 
* gz, bzip2, or xz-If given a file as an argument, gzip compresses the file, adds a “. gz” suffix, and deletes the original file.
* chmod -chmod is the command and system call used to change the access permissions of file system objects  sometimes known as modes. syntax Rcvf MODE,