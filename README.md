# Shortest Job First Scheduling Algorithm Simulator by Primesh Pathirana.

 Both Preemptive and Non-Preemptive SJF algorithms can be simulated. 

## Adding a process
![](https://github.com/PrimeshShamilka/Shortest-job-first-simulator/blob/master/s1.png)
## Gantt chart
![](https://github.com/PrimeshShamilka/Shortest-job-first-simulator/blob/master/s2.png)
## Viewing Results
![](https://github.com/PrimeshShamilka/Shortest-job-first-simulator/blob/master/s3.png)


## How to run

To run the Simulator clone the repository and open index.html file in your browser.


## SJF Scheduling Algorithm

Shortest Job First (SJF) is an algorithm in which the process having the smallest execution time is chosen for the next execution. This scheduling method can be preemptive or non-preemptive. It significantly reduces the average waiting time for other processes awaiting execution. The full form of SJF is Shortest Job First.

There are basically two types of SJF methods:

Non-Preemptive SJF
Preemptive SJF

### Non-Preemptive SJF
In non-preemptive scheduling, once the CPU cycle is allocated to process, the process holds it till it reaches a waiting state or terminated.

### Preemptive SJF
In Preemptive SJF Scheduling, jobs are put into the ready queue as they come. A process with shortest burst time begins execution. If a process with even a shorter burst time arrives, the current process is removed or preempted from execution, and the shorter job is allocated CPU cycle.

## Tech Stack Used

I have decided to use a JavaScript based web application to demonstrate the scheduling process. Following is the libraries I have decided to use in this project.

Am Charts	 - Add Gantt Charts to display data (https://www.amcharts.com/lib/3)

### Happy Coding!.

