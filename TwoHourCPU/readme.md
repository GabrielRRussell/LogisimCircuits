# TwoHourCPU
A very simple CPU that I made in a little over two hours.

Features:

1. Four Bit Operations

2. Four Operations: Add, Sub, AND, NAND

3. Two Four Bit Registers

4. 8 Bytes of RAM (16 Addresses, Four Bits Each)

5. A demo program

6. Instructions on how to make your own programs

7. A quick reset button to clear everything

____________________________________
How to write a program

It's pretty simple. The first two bits are the operation to perform (ADD,SUB,AND,NAND in that order).  
The third bit is a flag that allows you to ignore the operation and output a value directly  
The fourth bit selects whether you will be writing to a register, or RAM  
The next four bits are the address you will be writing to. If you are writing to a register, only the first bit is read (0000/0001 are the valid values for a register)  
The last four bits are the value that you would be writing if you choose to enable the output flag on the third bit.
