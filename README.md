KernelOSKU
==========

creating my own kernel dan os (operating System)
for compiling this is the methode 
1.nasm -f elf32   loader.asm -o kasm.o
2.gcc -m32 -c kernel.c -o kc.o
3.ld -m elf_i386 -T linker.ld -o kernel.bin kasm.o kc.o

