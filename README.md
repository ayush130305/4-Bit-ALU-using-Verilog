# 4-Bit-ALU-using-Verilog
A modular 4-bit ALU engineered in Verilog HDL and verified using Xilinx Vivado
This ALU performs essential arithmetic and logical operations on two 4-bit integers. It features a Ripple Carry Adder (RCA) for arithmetic operations, ensuring a deep understanding of carry propagation and hardware timing.

Key Features:
Arithmetic Operations: Addition, Subtraction (using 2’s complement), Multiplication, and Division.
Logical Operations: Bitwise AND, OR, XOR, and NOT.
Status Flags: Real-time generation of Carry, Overflow, Underflow, and Zero flags for branching logic.
Structural Modeling: Includes a custom-designed Ripple Carry Adder to optimize gate-level understanding.

Opcode,Operation,Description
000,ADD,A+B using Ripple Carry Adder
001,SUB,A−B via 2’s Complement Addition
010,MUL,4-bit unsigned multiplication (8-bit result)
011,DIV,Integer division (A/B) with zero-check
100,AND,Bitwise logical AND
101,OR,Bitwise logical OR
