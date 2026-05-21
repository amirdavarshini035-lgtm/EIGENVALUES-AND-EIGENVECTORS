# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: AMIRDAVARSHINI D
#RegisterNumber: 21225230013
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[2, 2],
              [1, 3]])

eigen_values, eigen_vectors = np.linalg.eig(A)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)

## Output:
<img width="1498" height="850" alt="Screenshot 2026-05-21 140127" src="https://github.com/user-attachments/assets/2e5025d9-ded4-4c90-8b82-373450e09f8c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
