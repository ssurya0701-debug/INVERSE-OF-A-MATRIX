# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: 
End the program
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
x=np.linalg.inv(a)
print(x)
## Output:
<img width="1227" height="360" alt="Screenshot 2026-10-16 085839" src="https://github.com/user-attachments/assets/b81687a0-b916-43eb-a7b1-5f36e7d24583" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

