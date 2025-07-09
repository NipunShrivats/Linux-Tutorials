# Linux

1. It is an open-source opertating system based on unix
2. It is known for its security, flexibility.

## History

1. created by Linus Torvalds in 1991.
2. The name "Linux" comes from Linus + unix

## UNIX

Unix is a powerful multiuser, multitasking operating system originally developed in the 1970's at AT&T's Bell labs, which served as the foundation for many modern operating systems.

## Linux Vs Unix

1. Unix is licensed Whereas Linux is Open Sourced
2. Linux is isnpired by Unix and is designed to be Unix-like.
3. It follows many of the same principles and standards, making it compatible with unix software and commands.
4. Linux is inspired by unix and so is MacOS.

## Linux is not a complete OS

1.  Linux is an open-source Kernel.
2.  A kernel(heart of Linux) is the core part of an operating system, managing system resources and communication between hardware and software.

## Linux Distributions(Distros)

Now using Linux, different companies are making their OS like Linux Ubuntu, Linux Fedora etc., which are proper OS aka Linux Distributions.

# Linux Basic Commands

1. date :
   to display date and time

2. ls :
   list everything in the directory

3. mkdir <directory name> :
   to make a new directory

4. ls -l :
   gives necessary info about the directories in the current flder like name, owner datetime of making

5. pwd :
   info about the current directory

6. touch <file name> :
   to make a file in current directory

7. rm <file name> :
   remove file

8. rmdir <directory name>
   remove directory

9. rm -r <file or directory name> :
   a. force remove file or directory
   b. will remove a directory even if there are files or folders ina directory

10. echo "hello world" :
    print data on terminal

11. echo "hello world" > newFile.txt
    store data in a file

12. cat <file name>: (regular files like txt)
    a. view stored data of a file
    b. will create a file and store data in it if file not found.

13. gzip filename.txt
    Compress a txt file (.txt -> .txt.gz) and delete original file.

14. gzip -c fileName.txt > fileName.txt.gz
    will compress a txt file & keep its original copy.

15. zcat <file name>: (newFile.txt.gz)
    a. zcat means compressed cat.
    b. used to show content of an already compressed txt file (.gz).

16. head <file name>:
    gives first 10 lines as output.

17. tail <file name>:
    gives last 10 lines as output.

18. less/more <file name>:
    a. data in pages form, also gives us controls
    controls:-
    a. up and down arrow key
    b. shift+g for going at bottom
    c. g+g for going at top
    d. /<word> to search
    e. press "q" to exit from screen
    f. man <less/more> options
