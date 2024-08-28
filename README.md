
Name: Naini Rakesh

Company: CODTECH IT SOLUTIONS

ID: CT6WDS1647

Domain: VLSI

Duration: AUGUST to SEPTEMBER 2024

Mentor: NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT

Project : FLOATING POINT UNIT (FPU) DESIGN

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


