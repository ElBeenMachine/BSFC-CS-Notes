# Processor Scheduling

## **About**

* Multitasking operating systems must enable multiple programs to be executing at the same time.
* Even within one program, there may be multiple programs to execute simultaneously.
* For this to be possible, a multitasking operating system will require a scheduler.

## **The Need for Scheduling**

* Processes as many tasks as possible in set time
* Makes maximum use of CPU time
* It will try to minimise the delay between when the user requests something to be done and when that task is completed.
* Makes maximum use of resources such as input-output devices
* Can prioritise jobs
* It will ensure that no task is left uncompleted for too long, even if they are low priority
* Can alter priorities according to need

## **Scheduler**

* Manages what process to execute next and how much time it is allowed to execute for.
* A new process would join the process read queue.
* When the currently executing process in the CPU either finishes or is stopped it will either finish execution completely (and leave the system) or it may be blocked (because of input / output command) meaning the process cannot continue until more data is received. It could also be given a certain amount of time before it must pause its execution in which case it will return to the ready queue so another process can be executed.
* There are several algorithms the operating system may be using to manage the processes in the ready queue.

## **Process Ready Queue Algorithms**

### **First Come First Served**

* The processes are executed strictly in the order in which they arrive.
* If one process takes a long time, the others must wait.

### **Shortest Job First**

* The scheduler picks the process that takes the shortest amount of time and runs them until they finish.
* The scheduler needs to know how long each process will take in advance.

### **Round Robin**

* Each process is allocated a fixed amount of time known as a time slice or quantum.
* If the process is not complete at the end of the quantum, it returns to the back of the ready queue so the next process can have its turn.
* It is fair, but not always efficient.

### **Shortest Remaining Time**

* Similar to shortest job first, but processes can be suspended if a higher priority process joins the queue.
* When the process no longer has the shortest remaining time, it is suspended until it has the shortest remaining time again.

### **Process Blocked**

* Happens when a running process requires data from the hard disk.
* The process is blocked until its request is serviced (interrupt).
* Generated to tell the scheduler that the blocked process can return to the process ready queue.

### **Multilevel Feedback Queues**

* Where the number of queues is increased.
* Different queues have different priorities, and the scheduler can move jobs between the queues
