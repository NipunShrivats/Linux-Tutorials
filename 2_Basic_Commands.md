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

19. cp Directory1/file1 Directory2:
    a. will copy file1 from Dir1 to Dir2

20. cp -r Dir1/ Dir2/: (-r = recursively)
    Will copy Dir1 inside Dir2

21. mv Devops/devops-file.txt Cloud/
    when outside the directory

mv devops-file.txt ../Cloud/
when inside the Directory

22. wc <filename.txt>: (wc -> word count)
    a. read no. of lines, words and size(in bytes).
    b. eg:- 3 12 51 newFile.txt

23. ln <path/filename>
    a. Create a hardLink of the file (not a shortcut [ln -> link])
    b. will no be deleted if main file is deleted
    c. changes in main file will reflect here

24. ln -s <path/filename>
    a. Create a softLink of the file (shortcut [-s -> soft])
    b. will be deletd if main file is deleted
    c. changes in main file will re flect here

25. cut -b 1/1-4 <fileName.txt>
    a. will give the data in the file according to alphabets
    b. 1 will give 1st alphabet and 1-4 give 1st 4 alphabets

26. echo "This is a new file" | tee newFile.txt
    a. this will print data on the screen & will create a file and save its data as well.

27. sort <fileName>
    a. will sort

28. diff <file1.txt> <file2.txt>
    a.differenec between 2 files data

29. vi/vim <fileName.txt>
    a. opens a file to edit
    b. press esc
    c. :wq! (write quit)
