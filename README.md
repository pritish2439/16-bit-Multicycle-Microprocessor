# 16-bit-Multicycle-Microprocessor

Custom 16-bit Multi-cycle Processor

This project involves the design and implementation of a custom 16-bit multi-cycle processor using Verilog and Xilinx Vivado. The processor supports a variety of arithmetic, logical, load/store, and control operations, and includes program and data memory along with special purpose registers for handling multiplication operations.

Features
Multi-cycle Architecture: Utilizes a finite state machine (FSM) to break down instruction execution into multiple stages (fetch, decode, execute, and control flow).

Arithmetic Operations: Supports addition, subtraction, and multiplication.

Logical Operations: Includes bitwise operations such as AND, OR, XOR, XNOR, NAND, NOR, and NOT.

Load/Store Instructions: Facilitates data transfer between registers and memory.

Control Instructions: Implements jump and branch instructions based on condition flags.

Condition Flags: Integrates sign, zero, overflow, and carry flags for effective branching decisions.

Files
top.v: The main Verilog file containing the processor implementation.

processor_memory.mem: Memory file for initializing the program memory.

Modules

Program and Data Memory: Implemented as arrays to store instructions and data.

General Purpose Registers (GPR): 32 registers for general computations.

Special Purpose Register (SGPR): Used for storing the most significant bits of multiplication results.

Instruction Register (IR): Holds the current instruction being executed.

FSM: Controls the state of the processor, managing instruction fetch, decode, execution, and halt operations.
