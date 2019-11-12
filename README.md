# JOS-Kernel-Programming
The lab exercises are based on the MIT 6.828 Operating Systems Engineering course (Fall 2017)
(https://pdos.csail.mit.edu/6.828/2017/)
These lab exercises focus on fundamentals of developing operating systems such as virtual memory, kernel and user mode, system calls, threads, context switches, interrupts, interprocess communication, coordination of concurrent activities, and the interface between software and hardware. 
The labs are structured as follows.

Lab1: Lab1 concentrates on getting familiarized with x86 assembly language, QEMU x86 emulator, PC's power-on bootstrap procedure and boot loader for JOS kernel.

Lab2: This lab focuses on writing the memory management code for the operating system. The major tasks include maintaining data structures that record which physical pages are free and which are allocated, and how many processes are sharing each allocated page, writing routines to allocate and free pages of memory and modifying the JOS to set up the MMU's page tables according to the specification provided.

Lab3: Lab3 implements the basic kernel facilities required to get a protected user-mode environment (i.e., "process") running. Major contributions include enhancing the JOS kernel to set up the data structures to keep track of user environments, creating a single user environment, loading a program image into it, and start it running. Also the JOS kernel is made capable of handling any system calls the user environment makes and handling any other exceptions it causes.

Lab4: This lab is based on preemptive multitasking among multiple simultaneously active user-mode environments. It implements multiprocessor support to JOS, round-robin scheduling, basic environment management system calls (calls that create and destroy environments, and allocate/map memory), Unix-like fork(), which allows a user-mode environment to create copies of itself, support for inter-process communication (IPC), allowing different user-mode environments to communicate and synchronize with each other explicitly and support for hardware clock interrupts and preemption.

Lab5: Lab5 focuses on the implementation of spawn, a library call that loads and runs on-disk executables and modification of kernel and library operating system enough to run a shell on the console. This lab also introduces a simple read/write file system.

Lab6: This lab concentrates on writing a driver for a network interface card. The card is based on the Intel 82540EM chip, also known as the E1000.
