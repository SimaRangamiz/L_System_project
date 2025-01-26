This project implements and visualizes L-systems, a method of generating fractal-like structures using recursive string rewriting. The code consists of three separate L-system simulations that create intricate patterns based on different sets of rules and axioms.

Features
L-system Generation: The L-system is generated by iteratively applying production rules to an initial axiom.
Recursive String Rewriting: Each rule replaces characters in the axiom with new strings in a recursive manner.
Visualization: The generated L-system is visualized using matplotlib, with each segment of the fractal being drawn using a defined set of commands.

How It Works
L-System Function:
The L-system is built by starting with an initial axiom and applying production rules iteratively for a specified number of iterations (depth).
The rules are defined in a dictionary where each character in the axiom is mapped to a string of replacement characters.
Drawing the L-System:

The drawing function interprets the generated string and converts it into a series of movements.
The directions are based on angle turns (left and right), and the movement is executed using a forward step ("F") that creates a line in the visualization.
Colors are assigned randomly to each segment of the path.
