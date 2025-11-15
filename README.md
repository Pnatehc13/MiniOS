My mini Os :
Im making a OS from scratch , this project is made with the goal of learning how an OS works 
Currently i made it till Paging and recently added user mode in it to 

now i will be documenting my journey of whole , also i did use AI as a guide for doing this project

# Mini-OS from Bootloader to Paging

## Key Features Implemented:

* **Bootloader:** A `boot.asm` bootloader (or configured GRUB) that switches the CPU to 32-bit Protected Mode and loads the kernel.
* **Kernel:** A small kernel written in C, handling the main OS logic.
* **Hardware Drivers:** Basic drivers for VGA text-mode (to print to the screen) and the PS/2 Keyboard (to read user input).
* **Interrupt Handling (IDT):** A full Interrupt Descriptor Table to handle hardware interrupts (like keyboard presses) and CPU exceptions (like Page Faults).
* **Physical Memory Manager:** A page frame allocator to manage all of physical RAM.
* **Virtual Memory (Paging):** A complete paging implementation (10/10/12 split) to create a virtual address space, providing full protection for the kernel and isolation for future processes.


  Any future implementation / updates would be updated here
  
