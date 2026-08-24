# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy and create the matrix using np.array().
### Step 2: Find eigenvalues and eigenvectors using np.linalg.eig().
### Step 3: Separate the returned values into eigenvalues and eigenvectors.
### Step 4: Display the eigenvalues and eigenvectors as the final output. 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: khovarthan.v
#RegisterNumber: 212225220052

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[2, 2],[1, 3]])

values, vectors = np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1209" height="158" alt="image" src="https://github.com/user-attachments/assets/8740c169-a831-4ef5-b3ef-0583a6c6e9eb" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
