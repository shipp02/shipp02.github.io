**Note: This is asm for MacOS. Tested to run on 10.15 catalina 
with nasm compiler installed via homebrew. You also need 
CommandLine Tools Installed**

# nasm 
- installation
`brew install nasm`
- [mannual](https://www.nasm.us/doc/)

## Sections:
Defined using:

``section .[section_name]``

**text**

This section is the one where code lives

**data**

Constant data definitions

**bss**

Reserve memory for usage in the program

# syscall 
-  refrence.
You can find all the syscalls for macOS in 

``/Library/Developer/CommandLineTools/SDKs/MacOSX10.15.sdk/usr/include/sys/syscall.h ``

- All syscalls must be prefixed with ``0x0200000``

- Syscall number must be moved into ``rax`` register

- basic syscalls
  1. Exit - `1`
  2. Print - `4`
  3. Read - `3`

# Registers
## General Purpose
- 16 registers 64-bit each

