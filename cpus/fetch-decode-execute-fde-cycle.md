# Fetch-Decode-Execute (FDE) Cycle

## **Fetch**

* The program counter points to the next instruction to be fetched.
* The contents of PC are sent / copied into memory address register.
* The address (contents of MAR) is sent along the address bus.
* A signal is sent from the control unit on the control bus.
* The content of address in memory is accessed and can now be transferred using the data bus into the MDR.
* If it is an instruction, the contents of the location in memory are sent to the current instruction register using the data bus.

## **Decode**

* Instruction in the CIR is decoded by the decode unit.
* Opcode gives the command; operand gives the data / address.

## **Execute**

* Address of the data is sent to the MAR which then sends it to the RAM.
* CU sends a signal down the control bus to read the data.
* Contents of memory is sent down the data bus to the MDR.
* Contents of the MDR normally then sent to the ACC depending on the instruction.
* After each execute the cycle is repeat.
