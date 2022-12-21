# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
For python mathamatics program first we want to import numpy 
### Step 2: 
Then assume a variable in that variable type np.array and the given value in the question
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
THen assume that values and vectors in that type np.linalg and the neigen vector
### Step 5:
Ten print the Eigen values and Eigen Vectors.
## Program:
```
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```
## Output:
![OUTPUT](./image/Maths%20ex%204.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
