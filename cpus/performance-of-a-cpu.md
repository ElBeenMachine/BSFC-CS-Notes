# Performance of a CPU

### Main Factors

* Clock speed
* Cache size
* Number of cores
* Width of buses
* Pipelining

### Clock Speed

* Controlled by the control unit.
* The speed of the FDE cycle is controlled by the clock speed.
* A CPU with a high clock speed will carry out more instructions per second and therefore have a higher performance.

### Cache

* Small, very fast memory.
* Filled with frequently accessed and next to be accessed instructions.
* Built into the CPU or placed on the motherboard.
* Faster to use cache than RAM.
* Generally, the larger the cache, the higher the performance.
* Most modern CPUs have three caches (L1, L2, L3).

### Number of Cores

* A multicore processor is made up of two or more independent cores.
* Each core is a distinct processing unit on the CPU with its own individual components and cache.
* A multicore CPU will have higher performance than a single-core CPU with the same clock speed.
* The biggest performance gain when using a multicore processor is when the software has been specifically written to run on multicore processors simultaneously.
* When multitasking different cores can run different applications or even run on the same one.

### Width of Buses

Word

* A word is a group of bits that refers to the number of bits used to store data in the CPU’s registers and cache.
* A larger word size means that the CPU will be able to process larger numbers in a single operation.
* A size or width of a bus is how many bits it carries in parallel.
* Modern CPUs have a 64bit word size.

### Width of Buses

* The width of the address bus determines the maximum possible memory capacity of the new system.
* A wider data bus can transmit larger values or more bites per instruction, and so as the data bus transmits the data held in memory, the word size affects the total amount of memory a computer system can handle.
* The largest value that can be held in a word is related to the size of the operating system.

### Pipelining

* Using pipelining, the computer architecture allows:
  * The next instructions to be fetched at the same time as the processor is performing arithmetic or logical operations.
  * Holding them in a buffer close to the processor until the instruction can be performed.
* Limitations:
  * It is not always possible to accurately predict what instruction needs to be fetched and decoded next. E.g. an instruction that acts differently depending on the result of a calculation.
  * Pipelining will choose one of the instructions to at least have a 50-50 chance of having the correct one.
  * But if the wrong instruction is chosen, we must “flush” all instructions from the pipe.
  * The more flushing that happens, the less benefit pipelining gives us.
