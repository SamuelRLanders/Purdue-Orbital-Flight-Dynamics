# Purdue-Orbital-Flight-Dynamics
This repository contians relevant files for Purdue Orbital Flight Dynamics tools.

User Defined Functions Notes:

User defined functions must be in a separate file that is different from the main code

File name for user defined function code must be the same as the function

Syntax:
First word must be function
Then output variables in an array (square brackets)
Then = name of the user defined function
Then input arguments from main code

function [output1,...,outputK] = functionName (input1,...inputK)


Do not need a return statement in the user defined function
Number of input and output arguments in function call must match the number of input and output parameters in function definition
If there is only one output, you do not need to put it in array
Inputs must always be inside parentheses
Comments must be on the next 3 lines
Cannot run the user defined function by itself
