# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation 
### Step 2:Prepare the lists from each Eigen values and Eigen vectors and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:PREM KUMAR G 
#RegisterNumber:23003614
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```
## Output:
![Screenshot 2023-12-13 111705](https://github.com/PremkumarG3/EIGENVALUES-AND-EIGENVECTORS/assets/138955646/03888ccd-69eb-437f-98ba-e371a12f149f)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
