# EXPERIMENT: 07
## Norm of a matrix
#### NAME: AVINASH T
#### REG NO: 212223230026
#### DEPARTMENT: ARTIFICIAL INTELLIGENCE AND DATA SCIENCE
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
 1.Hardware – PCs
 2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 1. Get the input matrix using np.array()   
 2. Find the 2-norm of the matrix using np.linalg.norm()
 3. 3. Print the norm of the matrix in two decimal places.
## Program:
```Python
#1-Norm of a Matrix
#Developed by: AVINASH T
#Register number: 212223230026
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matric="{:.2f}".format(ans)
print(Norm_of_matric)


# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: AVINASH T
#RegisterNumber: 212223230026
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matric="{:.2f}".format(ans)
print(Norm_of_matric)

# Infinity Norm of a Matrix
#Program to find infinity-norm of a matrix.
#Developed by: AVINASH T
#RegisterNumber: 212223230026
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matric="{:.2f}".format(ans)
print(Norm_of_matric)

```
## Input:
#### 1-Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/3846ee06-98f6-4965-8912-3ec6505908e9)
#### 2-Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/1f315f52-166c-4aa0-b83a-1161e444cfc9)
#### Infinity Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/ad7bab78-4f85-44aa-bce7-80bf94265970)


## Output:
#### 1-Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/162732b3-f4dc-4510-b123-69659d91e70d)
#### 2-Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/aa57b1b7-3ef1-4320-980f-202e0d2693ed)
#### Infinity Norm of a Matrix
![image](https://github.com/AVINASH05T/Norm-of-a-matrix/assets/151514286/317d199e-b163-4c41-9c04-6054fa8e0a17)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
