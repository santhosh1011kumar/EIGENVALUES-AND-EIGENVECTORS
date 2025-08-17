# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Santhosh kumar A
#RegisterNumber: 212224230250



import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(A)
print("Eigen values are", b, "and Eigen Vectors are",c)

## Output:
<img width="875" height="206" alt="image" src="https://github.com/user-attachments/assets/bbb0150e-a8e8-4bd2-ac57-d09eb7fd349e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
