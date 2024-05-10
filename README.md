                 
# 4-Bit ALU in VHDL

This project implements a 4-bit Arithmetic Logic Unit (ALU) in VHDL, capable of performing a wide range of arithmetic and logical operations on two variables. It offers a flexible and modular design, leveraging reusable components for adders, subtractors, logic gates, and multiplexers.
 
## Getting Started

-Clone this repository.
-Install a VHDL simulator (e.g., Xilinx ISE, ModelSim).

-Create a new project in your simulator and add the alu_4bits2sel.vhd file.

-Include any necessary component definitions from the other_components folder (if not using pre-built components).

-Configure your simulator's settings and provide test stimuli for num1, num2, cin, and sel.

-Run the simulation to verify the ALU's functionality for various operations.
 
## Built With

Components

-not4bit: Implements a 4-bit NOT operation

-or4bits: Implements a 4-bit OR operation

-fullAdder4bits: Implements a 4-bit full adder, supporting addition and subtraction

-and4bits: Implements a 4-bit AND operation

-mux4bits2sel: Implements a 4-bit 2-to-1 multiplexer


- [VHDL](https://www.contributor-covenant.org/)
- [Embedded Systems](https://creativecommons.org/)

