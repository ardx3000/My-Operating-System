# My Operating System
 
## Objective.
The main objective of this project will be to create an operating system from scratch that can perform simple computation and network communication.

## Tech stack.

### Languages
- C: Core system programming language.
- Assembly: For low-level hardware interaction.
- (optional) C++: For more complexe featuers.
- Python: for scripting and automation.

### Development Tools
- Cross Compiler: GCC with cross-compilation support for the target architecture.
- Assembler: NASM for x86 assembly.
- Debugger: GDB for debugging, QEMU for emulation.
- Build System: Make or CMake.

### Libraries and Frameworks

- libc: Minimal C standard library implementation, such as Newlib.
- Bootloader: GRUB to load your OS kernel.
- Networking Stack: lwIP (lightweight IP) for network communication.

## Development Environment
- Virtualization/Emulation: QEMU for testing.
- Version Control: Git.

## Core Components to Develop

### Bootloader

- Task: Initialize hardware, set up memory, load the kernel.
- Tech: Assembly, C.

### Kernel

- Architecture: Start with a monolithic kernel for simplicity.
- Subsystems: Scheduler, memory manager, file system, process manager, device drivers.

### Memory Management

- Task: Implement physical and virtual memory management.
- Tech: C.

### Process Management

- Task: Create process structures, scheduler, and context switching.
- Tech: C.

### File System

- Task: Implement a simple file system (e.g., FAT, ext2).
- Tech: C.

### Device Drivers

- Task: Write drivers for essential devices (keyboard, display, disk).
- Tech: C, Assembly.

### Networking

- Task: Implement a TCP/IP stack using lwIP or write a custom simple stack.
- Tech: C.
- Steps:
        Ethernet Driver: Write a driver to interface with the network card.
        Network Stack: Implement ARP, IP, ICMP, TCP, and UDP protocols.
        Sockets API: Provide an interface for applications to use the network stack.

### Shell and Utilities

- Task: Provide a command-line interface.
- Tech: C, possibly C++.

