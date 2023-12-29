# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

=======
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Define the matrix for which you want to find the rank

Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:
Display the calculated rank of the matrix


## Program:
```
#Program to find the rank of a matrix.
#Developed by: 
#RegisterNumber:
import numpy as np
matrix=np.array([[5,-3,-10],
                [2,2,-3],
                [-3,-1,5]])
rank=np.linalg.matrix_rank(matrix)
print(rank)
```
## Output:


![Alt text](image.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

