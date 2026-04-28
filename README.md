# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Given matrix
import numpy as np

A = np.array([[3, 2, 5],
              [1, 1, 2],
              [3, 3, 6]])

print(np.linalg.matrix_rank(A))
~~~
## Output:
<img width="1249" height="743" alt="Screenshot 2026-04-28 134312" src="https://github.com/user-attachments/assets/3ef5b350-f729-4f31-a449-1bb120e3a70b" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

