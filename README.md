# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PYNAM VINODH
#RegisterNumber:23004069
import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2023-10-28 133003](https://github.com/PYNAMVINODH/EIGENVALUES-AND-EIGENVECTORS/assets/145742678/cb4551df-fcc1-418d-ad72-087b54bf3e5a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
