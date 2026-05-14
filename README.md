# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors.

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:

### Step1 : 

Import the NumPy library using import numpy as np

### Step 2: 

Define the square matrix by entering its elements using np.array().

### Step 3: 

Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 

Store the results in two variables: one for eigenvalues and one for eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sivasakthi S
#RegisterNumber: 212225040418
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:

<img width="858" height="159" alt="image" src="https://github.com/user-attachments/assets/7cedd49a-e3b3-422d-a224-d6286eb5c0aa" />

## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
