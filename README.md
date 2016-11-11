#BANKER'S ALGORITHM
How to run the program:
1. Click the deadlocks.cpp

During program execution
You will be ask to choose between 3 numbers
	1. Deadlock Prevention
	2. Deadlock Avoidance
	3. Exit

1. Deadlock Prevention
	--USER INPUTS--
		-number of processes
		-process name and time allocation for each process
		-available resources
	**Then the state of the system and safe sequence will be displayed.
2. Deadlock Avoidance
	--USER INPUTS--
		-number of processes
		-number of resources
		-resource allocation of each process
		-maximum demand of each process
		-available resources
	**It will display the matrices for resource allocation, maximum demand and needed resources
	**It will display the system state and safe sequence (if there is)
	If the state of the system is SAFE, the program will ask if you want to add new request. If yes, you will be asked to choose which process to change the resources. Please only enter the process number (1,2,3).
	**It will again display the matrices, system state and safe sequence.

LIMITATIONS:
     1. Allows negative values to occur in the matrices
     2. No error checking for user inputs.
