# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Importing os and numpy module package.
### Step 2: Creating the given matrix in the python coderunner.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Printing the result.
## Program:
####Program to find the rank of a matrix.
#Developed by: Harish Bakavadh J
#RegisterNumber:26007865
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
B=np.linalg.matrix_rank(A)
print(B)
## Output:
<img width="1243" height="715" alt="image" src="https://github.com/user-attachments/assets/4f9505b4-89cd-40a0-a938-a65ce68a5ad9" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

