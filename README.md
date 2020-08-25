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
