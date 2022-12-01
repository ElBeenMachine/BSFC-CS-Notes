# Interrupts

## **About**

* The purpose of the CPU is to fetch, decode and execute instructions.
* However, peripherals and software may need attention and therefore need to signal the CPU. There are two ways of doing this:
  * Polling is where the CPU checks each device to see whether it needs attention. This is very inefficient, as if a device does not need attention, then there is no point in checking it.
  * Instead, a system called interrupts is used.
* A device sends a signal on the control bus to the CPU to indicate that it requires attention.
* If there is an interrupt, then the CPU needs to stop what it is doing and service the interrupt (by running the code to service the interrupt). This is known as an interrupt service routine.
* This creates a problem as the PC must keep track of the next instruction in the memory. If this must be changed to the first instruction of the interrupt service routine, then when the ISR is finished, how will the CPU know where to go in the previously executing program?
  * This is solved by using a stack. The contents of the PC are moved down to the stack, so that the first address of the ISR can be moved to the PC.
  * When the ISR is finished, the address in the stack can then be popped off the stack into the PC, and then the CPU knows where to continue executing instructions.
* Interrupts always have a higher priority than the current execution.

## **Types of Interrupts + Examples**

### **Hardware**

* Power / reset button is pressed
* Memory parity error (corrupt memory)

### **Software**

* Illegal instruction encounter
* Arithmetic overflow
* New logon request

### **Input / Output**

* Buffer nearly empty
* Signal the completion of a data transfer to / from a device.
