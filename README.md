Part 1: System Call Tracing
Responsibilities: Make an "empty" C program and then a program which produces exactly five more system calls than the aforementioned empty program.

Part 2: Timer Kernel Module
Responsibilities: Make a "timer.ko" kernel module that once loaded to the kernel produces the following behavior: the first time a user uses the command "cat proc/timer" it will print out the current UNIX Epoch time in a "seconds.nanoseconds" format, and in all subsequent times the user runs the commands it should print out the current time as well as the difference from the last time the file was printed, in the same format.

Part 3a: Adding System Calls

Part 3b: Kernel Compilation

Part 3c: Threads

Part 3d: Linked List

Part 3e: Mutexes

Part 3f: Scheduling Algorithm
