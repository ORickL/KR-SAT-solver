=================================================================================================================================
The core SAT solver program is the SAT.py file. 
To use this script from the terminal use the command line:
py SAT.py <input_file.txt> <heuristic>
=================================================================================================================================
Heuristics can be a choice of one of the following:
jw
moms
shortest_pos
sdk
random_abs
random
input_file.txt must be a text file in DIMACS format.
=================================================================================================================================
The output file is stored as a text file with the name: input_file.txt.out.
This file contains all the variable assignments 
=================================================================================================================================
EXAMPLE TO RUN SAT.py: to run the SAT.py on the test_problem.txt file with the random heuristic, use the following command line:
py SAT.py test_problem.txt random
=================================================================================================================================
experiment.py is the code used to run the experiments and keep track of various performance metrics.
generate_16x16_rule.py is the code used to make our own 16x16 sudoku rule file (16x16_gen_rules.txt)

