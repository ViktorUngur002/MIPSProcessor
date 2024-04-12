# MIPS single cycle processor project

On this project I worked with 4 other students. I was the software developer and my task was to implement the code, based on hardware schematic diagram made by the hardware team. I used Verilog for this project. First we had a task to develop a general purpose processor and later we had to specialize it for a calculator by adding two complex arithmetic operations(we implemented factorial and exponentiation operations). Also the code written is for a single cycle processor.

## Requirements
* Registers:
  * 16-bit Accumulator
  * 2 16-bit general purpose registers: X and Y
  * 4-bit Flag register: Zero, Negative, Carry, Overflow
  * 16-bit stack pointer
  * program counter
* Instruction size: 16-bit
  * 6-bit opcode
  * 1-bit Register address
  * 9-bit Immediate size
* Word size: 16-bit
* Stack grows inverse in memory
* Implementation of memory, branch, arithmetic and logic instructions
* Convert to an Application-Specific Instruction Set Processor
