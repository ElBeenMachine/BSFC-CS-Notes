# CPU Architecture

## **Von Neumann Architecture**

## **Components**

* Control Unit
* Arithmetic Logic Unit
* Memory Unit
* Registers
* Input / Outputs

## **Design**

* Instructions and the program data are stored in the same memory.
* It follows a linear fetch-decode-execute cycle.
* One instruction at a time.
* In particular, the same memory and bus are used for both data and instructions.
* In particular, the same memory and bus are used for both data and instructions.
  * A program must be placed in main memory to be executed.
  * The machine code instructions are fetched from memory one at a time, decoded and executed in the processor.
* This design is still used in most computers produced today.
* The same data bus is used to transfer both data and instructions.
* Similarly, a single address bus is used to transfer the address of data and instructions.
* The same word length is used for all memory, whether it holds data or instructions.

## **Von Neumann Bottleneck**

* Time required to move instructions from the CPU to the main memory and back can cause latency
* The CPU must wait a certain time which can be quite long. It could be shorter to access registers.
* To overcome this one possibility is to use cache, another is to use the Harvard architecture.

## **Harvard Architecture**

### Data and instructions are stored in:

* Separate memory units
* With separate buses
* Reading (fetching) data and writing data can be done at the same time as reading an instruction
* Tends to be used in RISC processors.

Modern high performance CPU chips incorporate aspects of both Von Neumann and Harvard architectures.
