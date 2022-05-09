# ReadMe
In this ReadMe file, an explanation of the program designed by group18 is given. This program is the first deliverable of the project for the subject ELEN4020. The files needed to run the program are provided (where are they provided?). The program makes use of the Jaguar Cluster with this group specifically using group18@jaguar.eie.wits.ac.za. (Also something about github).

# Explanation of the Code

There is one file in this folder: main.py

The file outputs a box and whisker plot based on the data which is input within the code itself (no user input is required). The file that the program is expecting is a csv file with 4 columns, the first being the time and the next being x, y and z variable respectively. 

To run the file, the instruction needed in the terminal is: ssmpiexec -hostfile machinefile -np 1 python3 ./runTest.pyh jaguar3.eie.wits.ac.za (if Jaguar 3 is being used??). np is the number of nodes which will be used to run the code with the minimum being 1 node and the maximum being the number of nodes on the cluster being used. 
