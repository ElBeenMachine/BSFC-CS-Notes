# Multi-Core and Parallel Systems

## **Multicore Processor**

* Single chip that contains two or more independent processing units (cores).
* Each core can execute ordinary CPU instructions on their own.
* Most manufacturers integrate these cores onto a single physical chip.
* This chip is known as a chip multiprocessor (CMP).
* They can be further enhanced by features such as sharing a local cache of memory and having some sort of inter-core communication system.
* Doubling the cores rarely equates to doubling the processing speed.
* Improvements on performance depend largely on the individual software programs being run.
* Typically, the gains in performance will be limited to the parts of the program that have been designed to run in parallel over the multiple cores.
* This is known as Amdahl’s law.

## **Parallel Processing**

* Parallel processing of program instructions by dividing them amongst multiple processors or processor cores, with the objective of running the overall program in less time.
* Often uses pipelining.
* There will be more than one processor / core in a complex operating system.
* The different processors will work together to execute a single job split into tasks.
* Each task can then be performed by any processor.
* Gains depend on the task and whether a program has been designed to make use of parallel.
