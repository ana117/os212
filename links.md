---
layout: default
permalink: /LINKS/
---

# LINKS

1. [Basic Linux Commands](https://www.freecodecamp.org/news/the-linux-commands-handbook/)<br>
60 basic commands with explanation and example.
For me, a total beginner, this links is useful because I'm not used to reading the built-in man command.

2. [AWK](https://www.gnu.org/software/gawk/manual/gawk.html)<br>
Official documentation(?) of AWK

3. [C Language](https://www.freecodecamp.org/news/the-c-beginners-handbook/)<br>
freeCodeCamp's beginner handbook for C.

4. [Bash Scripting](https://linuxconfig.org/bash-scripting-tutorial) & [for Beginners](https://linuxconfig.org/bash-scripting-tutorial-for-beginners)<br>
Bash scripting tutorial from LinuxConfig

5. [Unix File System](https://www.geeksforgeeks.org/unix-file-system/)<br>
Definition, structure visualization, and types of file system in unix. The structure is known as a directory tree with "/" (root)  at the top. Unix file system has 6 types of file, ordinary, directories, special, pipes, sockets, and symbolic links.

6. [File Allocation](https://www.geeksforgeeks.org/file-allocation-methods/)<br>
There are 3 methods, contiguous, linked, and indexed allocation. In contiguous, each file occupies a contiguous set of blocks on a disk. In linked, each occupied block have a pointer to the next block and can be scattered. In indexed, there's a special block called Index Block that contains the pointer to all blocks occupied by a file.

7. Memory Management | [Source 1](https://www.studytonight.com/operating-system/memory-management) | [Source 2](https://www.tutorialspoint.com/operating_system/os_memory_management.htm)<br>
Sources from internet about memory management. Includes addresses, allocation, fragmentation, paging, segmentation, and loading & linking. Might be useful for next quiz.

8. [Debian Bullseye Memory](https://www.debian.org/releases/bullseye/amd64/ch03s04.en.html)<br>
Debian official documentation said that 256MB is the minimum RAM for no desktop type. I tried going lower and got to 190MB memory (crashed at 180MB).

9. [Belady's Anomaly](https://www.geeksforgeeks.org/beladys-anomaly-in-page-replacement-algorithms/)<br>
Anomaly in page replacement algorithm where increasing the number of frame also increase the number of page faults. This anomaly usually occurs on FIFO algorithm when it doesnt follow the stack algorithm (the lesser frame is not a subset of the bigger one). Please correct me if I'm wrong :D

10. [Fork() Bomb](https://www.geeksforgeeks.org/fork-bomb/)<br>
Infinitely calling fork() can fill up your system memory making it unuseable. Fork bomb is a denial of service attack on Linux based system. One way to prevent it is by limiting allowed user's process in /etc/security/limits.conf

11. [Shared Memory](https://www.tutorialspoint.com/inter_process_communication/inter_process_communication_shared_memory.htm)<br>
Two or more processes (ex. parent and child from fork) can interact with each other using shared memory (one of IPC techniques). Shared memory, as the name implies, is a memory that is shared between multiple process. Some systems call related to shared memory is shmget(), shmat(), shmdt(), and shmctl().

12. [Semaphores](https://www.geeksforgeeks.org/semaphores-in-process-synchronization/)<br>
Semaphore is an integer variable that is shared between threads. Semaphore is used to prevent critical section problems. There are two types of semaphore, binary (aka mutex lock) and counting. You can increment or decrement the value using signal() or wait().

13. [Linux From Scratch](https://www.linuxfromscratch.org/)<br>
LFS is a project with step-by-step instruction on how to build your own Linux sysystem. You can create your own compact, flexible, and secure Linux system compared to existing distribution. You can also learn on how Linux system works internally.

