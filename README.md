# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: SUJIN M L
#RegisterNumber: 212225040435

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1334" height="853" alt="image" src="https://github.com/user-attachments/assets/292b3600-d692-430f-9218-95b722bba2f3" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

