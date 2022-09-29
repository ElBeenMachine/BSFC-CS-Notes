# Role and Components of A CPU

### Role of the CPU

The CPU carries out the FDE cycle

* Controls the movement of data and instructions
* Fetch data and instructions from memory
* Decode and execute instructions
* Perform arithmetic operations
* Perform logical operations

### Components in a CPU

* Registers are memory that hold any instructions, data and/or memory addresses that are about to be used by the CPU.
* Buses - Parallel wires connecting two or more components of the CPU.

#### Main Components

* Arithmetic logic unit - Completes arithmetic and logic operations such as adding or subtracting.
* Control Unit - Sends signals to control how the processor runs, and controls how data is moved around parts of the CPU and memory.
* Cache - Very fast memory in the CPU that is filled with frequently / next to be accessed instructions that are built into the CPU or placed on the motherboard.

#### Registers

* Program Counter - Stores address of next instruction
* Memory Address Register - Stores address of data to be fetched from or sent to memory.
* Memory Data Register - Stores data to be fetched from or sent to memory, like a middle man.
* Accumulator - Stores result of calculations by the arithmetic logic unit.
* Current Instruction Register - Stores actual instruction being decoded or executed.
* Interrupt Register - Checks to see if any interrupts require servicing.

#### Buses

* Address Bus - unidirectional, carries the address of data that is in the memory address register from the processor to memory.
* Data Bus - Bidirectional, carries data between the processor and memory.
* Control Bus - Bidirectional, carries control signal between processor and the components.

#### Control Unit

* Decodes instructions.
* Sends control signals down the control bus to coordinate the movement of data through the processor and execution of instructions.
* Controls and coordinates the activates of the CPU directing the flow of data between CPU and other devices.
* Controls buses.
