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
import numpy as np
A = np.array([[5, -3, -10],[2,  2,  -3],[-3, -1,  5]])
x = np.linalg.matrix_rank(A)
print(x)

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-19 201922" src="https://github.com/user-attachments/assets/9feac8a2-1a48-42e1-a78c-afc4235a47b8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

