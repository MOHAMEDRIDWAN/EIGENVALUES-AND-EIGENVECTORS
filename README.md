# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy module as np
### Step 2: create a matrix using np.array attribute and enter values of each columns and store ot in a variable
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: give print statement and end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOHAMED RIDWAN A
#RegisterNumber: 23003133

import numpy as np
A= [[2,2],[1,3]]
VALUES,VECTORS=np.linalg.eig(A)
print("Eigen values are",VALUES,"and Eigen Vectors are",VECTORS)
```

## Output:
<img width="515" alt="Screenshot 2023-12-21 235002" src="https://github.com/MOHAMEDRIDWAN/EIGENVALUES-AND-EIGENVECTORS/assets/146993368/b49eb6f7-3964-4590-ac8f-e6202045af69">

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
