# OS-CA
Question 2 implementation in c language
The Problem Statement
Considering 4 processes with the arrival time and the burst time requirement of the processes the scheduler schedules the processes by interrupting the processor after every 3 units of time and does consider the completion of the process in this iteration. The scheduler then checks for the number of processes waiting for the processor and allots the processor to the process but interrupting the processor after every 6 units of time and considers the completion of the process in this iteration. The scheduler after the second iteration checks for the number of processes waiting for the processor and now provides the processor to the process with the least time requirement to go in the terminated state.

Problem Explanation
This problem is based on the concept of scheduling algorithm which is used to allot process to the processor so that the time of the CPU can be utilized properly. Here the scheduling algorithm is based on Round Robin Scheduling with some other special condition and variable time quantum.
The proposed algorithm is supposed to follow the round robin scheduling with time quantum 6 time units for the first iteration and 10 time units for the second iteration and then work with the lengthiest job first (the process that requires more time first). The problem returns the waiting times and turnaround times of individual processes as well as the average waiting and turnaround time.
