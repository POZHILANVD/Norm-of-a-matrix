## DATE:
# EX.NO:7 Norm of a matrix.

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
#Register No: 212223240118
#Develop By: POZHILAN V D
#1-Norm of a Matrix 
import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: POZHILAN V D
#RegisterNumber: 212223240118
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

#Program to find 2-norm of a matrix.
#Developed by: POZHILAN V D
#RegisterNumber: 212223240118
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/fe6f1d66-1de8-42d2-bea9-28915b329174)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/3911decb-c1ab-47ee-8fa3-3c0194df52bb)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/de40b746-c5ae-443a-9e31-3cf9a4d678f6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
