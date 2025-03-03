# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np.
### Step 2:
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors,then end the program.

## Program:
```
#Program to find eigen values and eigen vectors
#Developed by:S VASUNTHARA SAI
#Register Number:212224230297

import numpy as np
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}") 
```

## Output:

![Screenshot 2025-03-02 214336](https://github.com/user-attachments/assets/7ca9c3ea-21c5-4305-a3d8-e4dfc35cb5ec)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
