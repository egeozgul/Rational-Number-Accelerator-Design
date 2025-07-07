# RPU

<p align="center">
    <img src="RLU_Block_Diagram.png" width="90%">
</p>

This repository contains the current VHDL implementation of a Rational Arithmetic Unit based on Binary Continued Logarithms as described in the included [Paper](Hardware_Development_of_a_Rational_Number_Arithmetic_Computation_Unit_Using_Binary_Continued_Logarithms.pdf).


# High-Precision Calculator Hardware

This project builds a specialized calculator chip that can perform math with perfect accuracy on decimal numbers. Unlike regular computer math that rounds numbers and loses precision, this system uses a new number format called Binary Continued Logarithms (BCLs) that stores numbers exactly without any loss.

The project has two main parts: first, developing the math theory behind BCLs; and second, programming the logic in VHDL (a hardware description language) to create a hardware design for the calculator.

This precise math is important for applications like banking software and scientific research where even tiny rounding errors can accumulate and cause big problems over time.
