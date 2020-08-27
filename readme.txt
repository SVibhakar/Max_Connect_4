Name - Sejal Nitinkumar Vibhakar
UTA ID - 1001765264


Programming language - Python


Structured of the code:
Initially, it takes input from command prompt. The input includes mode name (onemove or interactive), input file, output file for onemove or computernext or humannext for interactive mode and depth.
In one-move mode, the initialized state is the current game state from the input file. The aiplay function will implements the depth limited version of the minimax. 
In interactive mode, the current board game is initialised from the input file. If the input file does not exists, an empty board game is created. 
The interactivegame function will call the aiplay_interactive function with the current board game and then to the specified function based on the move specified [human-next/computer-next]from command prompt arguments. If the human-next is specified then the program will prompt the user to make the move and reponse is saved and written in the human.txt file and computer will now select it's turn. For computer turn the minimax function is called. After the computer's turn the changes
are saved and written to computer.txt file.
Utility values are calculated from the terminal_test function and the evaluation function eval_fn.

How to run the code?
For one move:	python maxconnect4.py one-move input_file_name output_file_name depth

For interactive game:	python maxconnect4.py interactive input_file_name [computer-next/human-next] depth
