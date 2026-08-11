# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy library
### Step 2: create a matrix using numpy
### Step 3: calc the result using np.linalg.inv
### Step 4: End the Program 

## Program: #Developed by: BHUVANESH.K
#RegisterNumber: 212224230037
import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(matrix)
print(inverse)
## Output: <img width="1245" height="947" alt="image" src="https://github.com/user-attachments/assets/c43e8324-6d61-441e-8dc4-b36ac57a835f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

