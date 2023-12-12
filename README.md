# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find Eigen Values and Eigen Vectors.
#Developed by: Mohamed Anas O.I
#RegisterNUmber: 23008005

import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2023-12-12 135312](https://github.com/Anas536/EIGENVALUES-AND-EIGENVECTORS/assets/139841834/7924c2eb-214b-4640-aff7-4c0d4f774669)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
