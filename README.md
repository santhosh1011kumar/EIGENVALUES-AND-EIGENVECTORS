# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors, then end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mukesh Raj D
#RegisterNumber:212224100038

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
```
## Output:

<img width="1920" height="1080" alt="MFA EXP--4" src="https://github.com/user-attachments/assets/4e04024f-4926-49de-8f1c-7c09b200015d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
