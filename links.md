---
permalink: LINKS/
---
<span style="color:red; font-weight:bold; font-size:larger;">By {{ site.author }}</span>
<br><br>
[HOME]({{ site.baseurl }}/) ---
[LINKS]({{ site.baseurl }}/LINKS/) ---
[PUBLIC KEY]({{ site.mypublickey }}/TIPS/) ---
[LOG]({{ site.baseurl }}{{ site.myloglink }}) ---
[TARBALL]({{ site.tarballlink }}) ---
[GITHUB]({{ site.githublink }})
<br>
<hr>

# LINKS

## W01 Overview 2, Virtualization & Scripting
1. [OS222 Course Main Link](https://os.vlsm.org/)<br>
Definitely the most useful link for those who enroll this course. It provides all you need. Just gotta read it 😫

2. [Vi Basic Commands](https://www.cs.colostate.edu/helpdocs/vi.html)<br>
Basic commands for vi. Can be used for file-related tasks. I'd rather just see those commands through here than memorizing all of them.

## W02 Security, Protection, Privacy, & C-language
3. [Digital/Online Privacy](https://www.freecodecamp.org/news/the-beginners-guide-to-online-privacy-7149b33c4a3e/)<br>
Online privacy matters less now. When you share your personal data throughout companies, there’s no guarantee that they’ll keep them safe.

4. [Cyber Security Introduction](https://www.youtube.com/watch?v=rcDO8km6R6c)<br>
An intro to cyber security. What is it? How to apply it? What could possibly threatens it?

5. [Secure Hashing Algorithm](https://www.howtogeek.com/363735/what-is-a-checksum-and-why-should-you-care/)<br>
One of the cyber security concept, Secure Hashing Algorithm (SHA in the W02 assignment). Basically it encrypts our text with a hash function.

## W03 File System & FUSE
6. [Fuse in linux kernel](https://www.kernel.org/doc/html/latest/filesystems/fuse.html)<br>
Explains what fues is and what are the commands. This site also explains the kernel side. Can be a good start for understanding fuse.

7. [Linux FHS](https://www.geeksforgeeks.org/linux-file-hierarchy-structure/)<br>
FHS stands for File Hierarchy Structure. It tells you where and how files are being stored in directories. Each directory has it's own purposes and all of them appear under the root directory.

8. [FHS (short version)](https://www.youtube.com/watch?v=42iQKuQodW4)<br>
FHS on 100 seconds. Short yet understandable. It can provide you the basic knowledge. Suitable for those of you who don't have much time or not really enjoy reading.

## W04 Addressing, Shared Lib, & Pointer
9. [Logical vs Physical Memory Address](https://www.geeksforgeeks.org/logical-and-physical-address-in-operating-system/)<br>
Logical address appears to be a refference to the physical address. In other words, physical address is the real address of the required data on the memory. Logical address is mapped to it's correspondensing physical address by a hardware called Memory-Management Unit (MMU).

10. [Memory Management with Address Binding](https://www.techwalla.com/articles/what-is-address-binding)<br>
One of the memory management implementations, conducted by the OS and the app that requires access to memory. It allocates a physical memory location to a logical pointer. This can be done by associating a physical address to a logical address, also known as virtual address.

11. [Linux Memory Mapping](https://frameboxxindore.com/linux/what-is-memory-mapping-in-linux.html)<br>
Memory mapping is a mapping mechanism of some files on a storage disk to a range of addresses within an application's address space. The application can then access files on disk in the same way it accesses dynamic memory. In linux, it maps the disk sectors of a file into the virtual memory space of a process.

12. [Another Memory Managements Concepts - Contiguous, Swapping, and Fragmentation](https://www.guru99.com/os-memory-management.html)<br>
More concepts on how OS manages memory. Store data on memory in a contigous way, swapping from the main memory and backing store, and also free memory spaces that are too small to be allocated by any processes.

## W05 Virtual Memory
13. [Virtual Memory Basic Concept](https://www.geeksforgeeks.org/virtual-memory-in-operating-system/)<br>
a Quick guide to virtual memory. What defines a virtual memory? How does it work? What are the types of it?

14. [Demand Paging](https://www.javatpoint.com/os-demand-paging)<br>
It is difficult to decide which pages need to be kept in the main memory and which are not. This is where demand paging come in handy. It keeps all pages in the storage until they are needed. In other words, first-time referenced pages will always be found in the storage.

15. [Page Replacement Algorithms](https://www.studytonight.com/operating-system/page-replacement-algorithms-in-operating-system)<br>
Conducted to reduce the number of page faults (current programs attempt to access pages that currently unavailable in the physical memory). These algorithms can help determining which pages should be swapped out from the main memory in order to create free space for the required pages in the main memory.

## W06 Concurrency: Processes & Threads
16. [Process or Thread?](https://www.javatpoint.com/process-vs-thread)<br>
Process in computer means following a required set of steps before executing a program. Meanwhile, thread is the subset of a process. A process may have more than one threads. These threads are managed independently by scheduler.

17. [Forking in C](https://www.geeksforgeeks.org/fork-system-call/)<br>
Forking can be used for creating new process called child process. This child process runs concurently with the parent process (which calls the fork() function). Both process will execute the next instruction after the fork() call. They use the same program counter, registers, and open files.

18. [Scheduling processes](https://www.tutorialspoint.com/operating_system/os_process_scheduling_algorithms.htm)<br>
In order to manage multiple processes, a computer needs a scheduler. It schedules different processes to be assigned to the CPU based on certain scheduling algorithm, some of them are: FNFC, SJN, and RR.

<br>
<hr>
&copy; {{ site.copyright }} --- {{ site.author }} --- Version: {{ site.version }}.
<hr>
<br>
