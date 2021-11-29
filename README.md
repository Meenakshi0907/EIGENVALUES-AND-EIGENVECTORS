# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy package.
### Step 2: Get the input matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Meenakshi M 
#RegisterNumber: 21003572
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vector=np.linalg.eig(a)
print("Eigen values are {0} and Eigen Vectors are {1}".format(values,vector))
```
## Output:
![output](./eigen.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
