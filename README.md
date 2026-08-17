Half Subtractor Using Verilog

Description

A Half Subtractor is a combinational digital circuit used to subtract one single-bit binary number from another single-bit binary number.

It has two inputs:

- A – Minuend
- B – Subtrahend

It produces two outputs:

- Difference (D)
- Borrow (Bout)

The Half Subtractor performs the operation:

A - B

The circuit can be implemented using XOR and AND/NOT logic gates.

Truth Table

A| B| Difference| Borrow
0| 0| 0| 0
0| 1| 1| 1
1| 0| 1| 0
1| 1| 0| 0

Logic Equations

Difference = A XOR B

Borrow = (~A) AND B

Objective

The objective of this project is to design and simulate a Half Subtractor using Verilog HDL and understand the basic principles of binary subtraction and combinational logic circuits.

Features

- Two 1-bit inputs
- Difference output
- Borrow output
- Combinational logic design
- Verilog HDL implementation
- Self-checking testbench
- Simulation output included

Files

half_subtractor.v       → Main Verilog design
half_subtractor_tb.v    → Testbench
simulation_output.txt   → Expected simulation output
README.md               → Project documentation

Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- GitHub


Author 

Sravanthi 

Applications

- Binary subtraction
- Arithmetic circuits
- ALU design
- Digital calculators
- Digital electronics
- FPGA and ASIC design

Conclusion

The Half Subtractor successfully performs subtraction of two single-bit binary numbers. The simulation verifies all possible combinations of inputs and confirms the correct Difference and Borrow outputs.