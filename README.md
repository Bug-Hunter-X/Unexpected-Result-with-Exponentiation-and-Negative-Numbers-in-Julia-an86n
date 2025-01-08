# Julia Exponentiation Bug
This repository demonstrates a subtle bug in Julia related to the precedence of the exponentiation operator (`^`) when combined with negative numbers and conditional statements.

The `bug.jl` file shows a function that squares a number, intending to return the square even for negative numbers. However, due to operator precedence, negative input produces unexpected results.  The `bugSolution.jl` file provides a corrected version.

This example highlights the importance of carefully considering operator precedence in Julia to avoid unexpected behaviour.