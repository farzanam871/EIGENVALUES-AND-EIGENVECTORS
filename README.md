# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :import the numpy module to use the build-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: Farzana M

#Register no.: 212225040087
import numpy as np

A=np.array([[2, 2], [1, 3]])

eigenvalues, eigenvectors=np.linalg.eig(A)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")


## Output:
<img width="1312" height="1035" alt="image" src="https://github.com/user-attachments/assets/502c52ff-377f-4825-a789-9510dd6eca77" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
