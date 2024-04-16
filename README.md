# EIGENVALUES-AND-EIGENVECTORS
# Date: 
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing the NumPy library. 
### Step 2:
Define the given matrix A.
### Step 3: 
Use np.linalg.eig(A) to find the eigenvalues and eigenvectors.
### Step 4:
print and end the program.

## Question:

Write a program to find the eigenvalues and associated eigenvectors for the matrix [2,2],[1,3]

## Program:
```
Developed by:Madhu mitha V
RegisterNumber:2305002013
```
```python
import numpy as np
A=np.array([[2,2],[1,-3]])
values,vector=np.linalg.eig(A)
print("Eigenvalues are {} and Eigenvectors are {}".format(values,vector))
```

## Output:
![image](https://github.com/Madhumitha2006/EIGENVALUES-AND-EIGENVECTORS/assets/155508589/27bdf7e4-5d88-4eb7-a480-360184c37e91)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
