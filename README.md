# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Kellan Carrillo, Austin Hart

## Lab Summary
In this lab we applied our minTerm and maxTerm solutions for K-Maps and applied them the output function of our circuit a and b files. Then we connected our circuit in top.v assigning the inputs and outputs for our functions on the board and assigned out variables to the ports on the BASYS 2 board. Additionally we made the output of circuit a connect to circuit b by assigning the led output for circuit a as an input for variable A of circuit b. Finally we applied our code to the board by running the simulation, generating the bitstream, and programming the BASYS 2 board. We checked this by testing the circuit through inputs from the switch and the given outputs on the truth tables. 
## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file assigns the physical input and outputs on the board. Then we are able to assign individual variables in our files to the switches and leds on the board so we can test our program. Ultimately the top level file applies our coded files to the board.

### 2 - Explain the function of the Constraints file.
The constraints file pulls through the names of variables through our top level file and passes them through to the BASYS 2 board and sets the physical location of the switches.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Our selection of the minterm and maxterm was correct for each cirucuit. Circuit a only needed one group of four, proving the most effective equation. Additionally circuit b allowed us to create 3 groups for our maxterm equations. Both of our files had the most efficient selection for the chosen minterm and maxterm.

