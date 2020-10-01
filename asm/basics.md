**Note: This is asm for MacOS. Tested to run on 10.15 catalina with nasm compiler installed via homebrew.**

# nasm installation
`brew install nasm`

## syscall refrence
- You can find all the syscalls for macOS in 

``/Library/Developer/CommandLineTools/SDKs/MacOSX10.15.sdk/usr/include/sys/syscall.h ``

- All syscalls must be prefixed with ``0x0200000``

## basic syscalls

1. Exit - `1`
2. Print - `4`
3. Read - `3`

## general purpose registers
- 16 registers 64-bit each

