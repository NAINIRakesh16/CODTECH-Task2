
Name: Naini Rakesh

Company: CODTECH IT SOLUTIONS

ID: CT6WDS1647

Domain: VLSI

Duration: AUGUST to SEPTEMBER 2024

Mentor: NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT

Project : FLOATING POINT UNIT (FPU) DESIGN


![image](https://github.com/user-attachments/assets/abc89ba3-2a84-4c32-afc1-acf5a6439d2b)



![image](https://github.com/user-attachments/assets/526ae12e-bb6e-42c5-b5b4-841d8a71fca7)


![image](https://github.com/user-attachments/assets/aff47803-0b51-4565-a0a7-9045d9da35d3)


![image](https://github.com/user-attachments/assets/23dbf874-f2ae-4fc8-bdc4-a30a5e9028d3)




Software:

- Verilog: A hardware description language (HDL) used for designing and testing digital circuits.
- Testbench: A Verilog module that provides input stimuli and checks output responses for a device under test (DUT).

Key Points:

1. Module Declaration:
    - FloatAdditionTB: Testbench module name.
    - XLEN = 32: Parameter defining the bit width of floating-point numbers.
2. Registers and Wires:
    - A and B: Input registers for floating-point numbers.
    - clk: Clock signal register.
    - overflow, underflow, exception: Registers for flags.
    - result: Output wire for the result.
3. Floating-Point Addition Instance:
    - FloatingAddition F_Add: Instantiates the floating-point addition module.
4. Test Vectors:
    - Five test cases with different input values.
5. Expected Value Calculation:
    - Computes the expected result using the formula: (2^(exponent-127)) * (mantissa/2^23) * (-1)^sign.
6. Display Results:
    - $display prints the expected value and result for each test case.
7. Simulation Control:
    - #20 waits for 20 time units between test cases.
    - $finish ends the simulation.

Key aspects:

- Verilog testbench for floating-point addition
- Five test cases with varying input values
- Expected value calculation using the IEEE 754 floating-point representation formula
- Displaying results for comparison
- Simulation control using Verilog timing constructs

This testbench verifies the functionality of the floating-point addition module by providing various input scenarios and checking the output results.


