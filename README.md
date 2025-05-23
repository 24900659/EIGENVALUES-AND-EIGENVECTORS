# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the necessary library, numpy, for matrix operations.
### Step 2: 
Define the given matrix using the numpy.array() method.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Display the eigenvalues and eigenvectors using the print() function.


## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: Mohana K.V.S.L

#RegisterNumber: 24900659
import numpy as np

a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors=np.linalg.eig(a)

print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

## Output:
![Screenshot 2025-05-16 194522](https://github.com/user-attachments/assets/ea8648d9-4931-4ceb-ba7e-1e753a86569f)
![Screenshot 2025-05-16 194535](https://github.com/user-attachments/assets/87b8466b-a594-43b7-abc7-628e299fca60)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
