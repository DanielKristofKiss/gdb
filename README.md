
GDB hack to make it work on ARM with dwarf,mach_o binaries.

- tested with QEMU 2.1.2 ARM
- it is not perfect.
- creted for xnu_on_arm project

Steps to build:

./configure --target=arm-none-elf

make

