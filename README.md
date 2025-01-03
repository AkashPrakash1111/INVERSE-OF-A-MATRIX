# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :input Matrix 3x3 matrix as variable named matrix as nested list 
### Step 2:compute the nested list as determiant is non-zero,print,that the matrix is non-invertible abd stop. 
### Step 3:compute if the determinant is non-zero,use np.linalg.inv(matrix) to compute the inverse.
### Step 4:print the inverse matrix. 
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Akash Prakash
#RegisterNumber: 24008757
import numpy as np
mtx=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(mtx)
print(inverse)
```
## Output:
![Screenshot 2024-12-01 153206](https://github.com/user-attachments/assets/620fb714-efe4-47b7-846c-6627d76d97c2)

## Result:
Thus the inverse of given matrix is successfully solved using python program

