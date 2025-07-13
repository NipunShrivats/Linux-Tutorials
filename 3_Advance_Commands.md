# Linux Advance Commands

SSH (port 22)
a. Local user should have "private key" and remote server should have a "public key"
b. building a ssh connection while working in AWS EC2 for local machine

## Disk usage

1. df (disc free)
   a.display info about disk usage.

2. du . (disc usage)
   a. displays disk usage of current directory.

3. ls -a
   a. all files and folder inc, hidden ones.

4. ps
   a. processes basic.

5. top
   a. total processes.

6. kill <id>
   a. Terminate processes manually.

7. free
   a. Snapshot of your system’s memory usage.

8. free -h
   b. Displays memory usage in a human-readable format.

9. nohup
   a. used to run processes that survive terminal hangups
   b. basically we can create logs.
   c. "nohoup free -h" this will record "free -h" comands' data without deleting teh previous data.

10. vmstat/vmstat -a (active & inactive)
    a. Performance monitoring tool that reports on system activity like memory usage, processes, CPU load, and I/O operations
