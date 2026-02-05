# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Firstly Import Numpy using import 
### Step 2: Then convert The List Of matrix into Array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Lastly,print the eigen values and eigen vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Surya Prakash S
#RegisterNumber:25014536/212224050443

import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/1c02debe-05a8-4ace-93aa-524b93443525" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
