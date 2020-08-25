# Assembler
Limited Instruction Set MIPS Assembler (implements 32 instructions).
[coded in Java]

This code is part of a bigger project for ECSE 425 Computer Architechture at McGill University (Winter 2016): 5-stage Pipelined MIPS Processor. 
(I believe the course instructors are also using my assembler since 2017).

Converts MIPS instructions into binary assembly. 

Implements assembly of a limited set of 32 instructions:

R-Instructions: mult, mflo, jr, mfhi, add, sub, and, div, slt, or, nor, xor, sra, srl, sll;

I-Instructions: addi, slti, bne, sw, beq, lw, lb, sb, lui, andi, ori, xori, asrt, asrti, halt;

J-Instructions: jal, jr, j;

Custom test instructions: asrt, asrti, halt

# How to use:

This MIPS assembler produces binary instructions given an .asm input file.

Many error cases and exceptions are handled, with relevant error messages printed to command line if such occur.

In order to create a binary output from a given .asm file, follow these steps:
1. Compile the assembler:
	javac Driver.java
2. Run the compiled Java program using the following syntax:
	java Driver filenama
	Note: filename must be a valid .asm file
3. Locate the resulting binary instruction file:
	The assembled file will be named filename.dat (name of the output is the same as the input file), 
	which will be located in the same directory as the input target.
