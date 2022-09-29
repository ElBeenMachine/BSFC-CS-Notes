# Memory Management

### **Paging**

* The memory is divided into smaller sections which are all the same size (each chunk called a page).
* Each program occupies a different number of pages.
* The program is split into pages, so they fit the free space pages.
* The operating system would use a page table to keep track of where in memory each of the pages are stored.
* This method therefore does not require all the pages to be stored continuously.

### **Segmentation**

* Does not consider what the instructions are doing in the sections of code that are separated.
* Keeps logical divisions of programs together rather than having fixed page sizes.
* Segmentation is slower than paging.

### **Similarities**

* Both allow programs to run despite insufficient memory.
* Both pages and segments are stored on disks.
* Both pages and segments are transferred into memory when needed.

### **Differences**

* Pages are a fixed size whereas segments are varied sizes.
* Pages are made to fit sections of memory whereas segments are complete sections of the program.
* Pages are physical divisions whereas segments are logical divisions.

### **Problems with Both**

* If physical memory is running low, virtual memory must be used. If more time is spent moving pages / segments in and out of the memory on the disk (thrashing) than processing the instructions, the computer will be slow.

#### **Virtual Memory**

* Moves the sections of the programs that are not being used out on the hard drive.
* When the sections of the program need to be used again they are sent back into the main memory.
* A lot of time is spent in moving instructions in and out of the RAM, known as disk thrashing (which makes the computer very slow.)
* The CPU cannot execute instructions from the disk.
