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
#Developed by: Santhosh kumar A
#RegisterNumber: 212224230250



import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
b,c=np.linalg.eig(A)
print("Eigen values are", b, "and Eigen Vectors are",c)
```

## Output:
<img width="1238" height="749" alt="image" src="https://github.com/user-attachments/assets/b9e4f9f3-fccd-4a00-8cda-dd60c97c86cb" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
