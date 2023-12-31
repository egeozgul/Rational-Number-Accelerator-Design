# RPU

<p align="center">
    <img src="RLU_Block_Diagram.png" width="90%" height="50%">
</p>

This repository contains the current VHDL implementation of a Rational Arithmetic Unit based on Binary Continued Logarithms as described in the included [Paper](Hardware_Development_of_a_Rational_Number_Arithmetic_Computation_Unit_Using_Binary_Continued_Logarithms.pdf).


## Abstract
In this project, an Arithmetic Computation Unit for operating on Binary Continued Logarithms (BCLs) is developed which is a
a novel decimal number representation That can represent any
rational number losslessly given a large enough width. The paper
first presents the mathematical theory that allows storing high precision decimal numbers, then it outlines the theory for performing mathematical operations on the type. After presenting
the mathematical theory, the custom type and operations are
implemented in VHDL and a hardware accelerator is built which
is dedicated to performing high-precision decimal arithmetic on
the type.
