# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy
### Step 2:
assign the values
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print and end the program
# Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sanjeevi J
#RegisterNumber: 212222110040
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```
## Output:
![WhatsApp Image 2023-04-08 at 20 25 23](https://user-images.githubusercontent.com/121484976/230728021-5f13aecc-41b3-4d49-bca2-73723221b797.jpg)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
