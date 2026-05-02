# MAI_EXP3
# Exp-03---Inverse-of-a-matrix
# Name: POOJA PRIYA B
# Reg no: 212224230196
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Read the given square matrix. 
### Step 2:Augment the matrix with the identity matrix of the same order. 
### Step 3:Apply row operations to convert the given matrix into the identity matrix.
### Step 4:The transformed identity matrix becomes the inverse of the given matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: POOJA PRIYA B
#RegisterNumber:212224230196

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])
B = np.linalg.inv(A)
print(B)

```
## Output:

<img width="750" height="353" alt="image" src="https://github.com/user-attachments/assets/18f26d4f-5641-49d4-98b7-70d4f7bd1f8d" />


## Result:
Thus the inverse of given matrix is successfully solved using python program
