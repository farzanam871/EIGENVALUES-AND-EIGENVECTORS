# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: Farzana M

#RegisterNumber: 212225040087

import numpy as np


A=np.array([[2, 2], [1, 3]])

eigenvalues, eigenvectors=np.linalg.eig(A)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
## Output:
<img width="1312" height="1035" alt="Screenshot 2026-02-13 210711" src="https://github.com/user-attachments/assets/eb93abf0-2dbe-4ad5-b53f-8ce746964b7d" />
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
