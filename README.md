# Elementary-Cellular-Automata-XNOR-Overlay-
Passes 00,01,10,11-->[1,0,0,1] For where the cells are either both 0 or both 1 per user input for which ECA the user would like to study. 

Cellular Automata Overlay Visualization Tool

This repository contains a Python script for visualizing the overlay of two cellular automata (CA) using the XNOR operation. Cellular automata are mathematical models that consist of grids of cells, each of which can be in a finite number of states. The state of each cell in the grid evolves over discrete time steps according to a set of rules based on the states of neighboring cells.
Features

    Generate cellular automata using two different rules.
    Apply XNOR operation to overlay the two generated CAs.
    Visualize the overlaid pattern.

Installation

To run this script, you need Python installed on your system along with the following packages:

    numpy
    matplotlib

You can install these packages using pip:

pip install numpy matplotlib

Usage

    Setting Parameters: The script allows you to set the total number of steps for evolution and the rule numbers for the two CAs. Adjust these parameters in the script to experiment with different patterns.

    python

    steps = 764  # Total number of steps to evolve
    rule_a = 18  # First rule number
    rule_b = 25  # Second rule number

    Generating CAs: The script generates two cellular automata based on the specified rules.

    Overlaying CAs: The two generated CAs are overlaid using the XNOR operation.

    Visualization: The overlaid pattern is visualized and displayed.

Functions

    rule_to_binary: Converts a rule number to its binary representation.
    apply_rule: Applies the CA rule to a given state.
    step_ca: Computes the next state of the CA.
    generate_ca: Generates a cellular automaton based on a specified rule.
    xnor_operation: Performs the XNOR operation on two arrays.


