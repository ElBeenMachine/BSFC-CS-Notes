# Input, Output, and Storage Devices

## **Input Devices**

* Any device that allows you to get information from the outside world into a computer system is an input.
* Input devices input information so it can be processed and stored into a digital form.

## **Output Devices**

* Any device that is able to take data which is stored in a digital form and then convert it into another format which humans can process is an output device.

## **Storage Device**

* A storage device is any computing hardware which is used for either temporary or permanent storage of data.
* Can be internal or external to the computer.

## **Primary Storage**

* The CPU can access this directly.
* Quicker data access.
* Mostly volatile.
* Registers.
* Cache.
* RAM.
* ROM.

## **ROM**

* Read only memory.
* Can only be read.
* Is non-volatile.
* Small chip built onto the motherboard.
* Why is ROM needed?
  * Contents cannot be changed by a program.
  * As soon as the computer is powered on, the CPU reads the instructions from the ROM.
  * Contains a chip with the instructions a computer needs to boot up called the BIOS.

## **RAM**

* High speed memory.
* Is volatile memory.
* Can be read from and written to.
* Why is RAM needed?
  * It is where all data, files and programs are stored while they are being used.
  * When a computer is powered on the operative system is copied from back storage into the RAM
  * When a program or files are used, they are also copied from the back storage to RAM.
  * The program or files stay in the RAM until the applications are closed and the changes must be saved to secondary storage to be retained.
  * RAM is slower than CPU cache but faster than secondary storage.

## **BIOS (Basic Input Output System)**

* BIOS is the program stored in EPROM (Erasable Programmable Read-Only Memory) that gets your computer started after you turn it on.
* It initialises the hardware ready to load the bootloader.

## **UEFI**

* Nowadays, most computers almost exclusively use the unified extensible firmware interface.
* UEFI is the successor to BIOS, however BIOS is often used as the term for both due to their similarities.
* UEFI achieves the same functionality as BIOS, in a more versatile and secure manner.

## **Bootloaders**

* The bootloader is a program that is loaded by the BIOS when a computer is first turned on, and is responsible for loading the operating system.
* It is necessary due to the complexity of creating a BIOS cable of loading hundreds of different operating systems.
* The bootloader is usually installed at the same time as the operating system, and is loaded from a known place on the hard drive by the BIOS.

## **Secondary Storage**

* Is not directly accessible by the CPU.
* Slower data access than primary storage.
* Non-volatile.

## **Secondary Storage Devices**

### **Magnetic Storage**

* Any devices that store data using magnetic fields. These include magnetic tapes, floppy disks and some hard disk drives.
* A series of magnetic disks known as platters are magnetised. A read / write head moves very close to the magnetic surface from the platter. The distance is normally only a few nm.
* These read / write disks are able to detect as well as modify magnetic properties of the metal platter. The changes in the magnetic field are detected and recorded as 1s and 0s.
* It is one of the cheapest forms of storage out on the market.
* Storage capacity is very large so it is good for companies / offices.
* Access times can be quite slow due to delicate and precise moving parts.
* Quite fragile, so not good for mobile devices.

### **Optical Storage**

* Any devices that work by shining a laser at the media and processing the reflection from the media.

#### **Read-Only**

* In the case of read-only drives such as CD-R and DVD-R the surface of the disk is physically burnt by the laser creating what are known as pits and lands suitable for storing 1s and 0s.
* It’s the point where the pit starts or ends which causes the laser light to scatter and thus is not reflected as well.
* It is this change of reflective and non-reflective areas which is read and interpreted as the 0s and 1s.
* Once the surface is burnt it cannot be burnt again making it read-only.

#### **Read-Write**

* In the case of writable drives (CD-RW / DVD-RW) the chemical composition of the disk is changed by a reversible chemical reaction.
* This means the data can be written many times.
* Cheap, lightweight and portable.
* Slow access times and often prone to scratches.

### **Solid State Storage**

* Any devices that store data directly onto silicone microchips as supposed to magnetically or optically.
* Uses a type of memory known as flash memory. (similar to RAM but non-volatile)
* Data is read & written directly to blocks and pages on the silicone microchips.
* As solid-state drives have no moving parts, they are much more durable than hard disk drives.
* Great choice for mobile devices and access times are very fast.
* A lot more expensive per byte, though prices are rapidly coming down.
* Each separate storage location on an SSHD can only be written to a limited number of times. Each time a block is re-written, a slightly higher voltage has to be used. Eventually, the required voltage is so high the entire block is useless.

## **Embedded Systems**

* Dedicated system designed for a fixed purpose.

### **Non embedded vs embedded**

#### **Non embedded**

* Usually, more RAM than ROM as they need to write data to main memory.
* ROM typically used for BIOS which doesn't require much memory.

#### **Embedded**

* Usually, more ROM than RAM as they don't need to write data to main memory.
* They don't tend to have secondary storage, so ROM is usually used to store all programs.

## **Virtual Memory**

* Programs are transferred out to virtual memory from the RAM when they are not currently being executed.
* Programs are transferred back to the RAM from virtual memory when they are needed.
* It is a memory that exists on the secondary storage but appears to be from RAM to the program that uses it.
* It helps the OS when physical RAM is limited, and big programs or data files need to be run.
* The OS uses to only load into RAM the part of a program or data file that is in use.
* The OS can then swap sections of the programs and the data files back and forth between the RAM and the Secondary Storage as they are needed and then finished with.
* The area of the hard disk that acts as the virtual memory is called a page file. The execution when using it is slower.

## **Performance**

* When a computer is in use the RAM must store the operating system, the programs and any data files that are in use.
* If a computer has too little RAM it may not be able to keep all application data loaded at once, slowing the system down.
* Not having enough RAM means more data will have to be swapped back and forth between the RAM and the Hard Drive.
* The more RAM, the more applications or more memory - intensive applications it can easily run, making it faster overall: higher performance.
