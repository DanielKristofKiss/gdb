
GDB hack to make it work on ARM with dwarf,mach_o binaries.
- tested with QEMU,xnu_on_arm project. 
- it is not perfect.

./configure --target=arm-none-elf
make

