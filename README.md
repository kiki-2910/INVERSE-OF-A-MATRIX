# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library and define the matrix.
### Step 2: Check whether the determinant of the matrix is non-zero.
### Step 3: Use np.linalg.inv() to compute the inverse of the matrix.
### Step 4: Display the inverse matrix.

## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([
    [2, 1, 1],
    [1, 1, 1],
    [1, -1, 2]
], dtype=float)

inverse = np.linalg.inv(A)

print(inverse)
## Output:
<img width="1267" height="771" alt="image" src="https://github.com/user-attachments/assets/f3f2bb63-de3a-47b3-bef4-fecc16c122ce" />
<img width="935" height="213" alt="image" src="https://github.com/user-attachments/assets/86744501-47eb-4221-a669-f1c0e1e85b5e" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

