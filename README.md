# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy to module to use the built-in function for calculation.
### Step 2: Initialize the given matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Stop the program

### Program:
### Program to find the eigen values and eigen vectors.
### Developed by:Jagadeep
### RegisterNumber:26015584
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### B,C=np.linalg.eig(A)
### print("Eigen values are",B,"and Eigen Vectors are",C)
## Output:
<img width="1285" height="802" alt="image" src="https://github.com/user-attachments/assets/20ff19c5-9782-450c-904f-69a58431daa9" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
