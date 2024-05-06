# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4. End the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SANTHOSH G
RegisterNumber: 212223240152
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SANTHOSH G
RegisterNumber: 212223240152
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

```

## Output:
## i)
![Screenshot 2024-05-06 130037](https://github.com/GSanthosh007/LU-Decomposition/assets/147527586/b281658a-5ae5-4654-a4fa-7eeccaa6227a)
## ii)
![Screenshot 2024-05-06 130056](https://github.com/GSanthosh007/LU-Decomposition/assets/147527586/24272cf7-ed65-4573-aca8-02c9c3f3c75d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

