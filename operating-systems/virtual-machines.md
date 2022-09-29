# Virtual Machines

### About

* Virtual machine definition: “A program that has the same functionality as a physical computer.”
* Emulators trick a program into thinking it's running on its native hardware when, in fact, it's running on an entirely different machine.
* Arcade games from the 1980’s can be emulated on today’s hardware.
* The programs themselves are completely unaware they are being emulated.
* The code is being executed exactly as it was originally - this is an example of a virtual machine.
* Another example of emulation in games development is to create the game on a PC but use an emulator for another device such as a games console or smartphone to test they program before release.

### **Server Technology and Virtual Machines**

* This technique can be used to support many virtual servers spread over a small number of physical servers.
* Here we have four physical servers, but they are running as six virtual servers.
* As demand on the network, additional servers can be spun up and the load balanced across different physical devices.
* Another major advantage of this is if one server stops working, the other can pick up the load and continue working as if nothing happened.

### **Virtual Machines and Intermediate Code**

* Java code is a good example of intermediate code running on a virtual machine.
* Java code is designed to run on many different platforms.
* With traditional programming, you would either have to use the specific language of each device or a suitable compiler for that device.
* Java gets around this by compiling its code into a half-way code known as bytecode or intermediate code.
* This code is translated by a java virtual machine running on a target device, which then translates it into a specific machine code.
* This process makes the code highly portable between devices.
