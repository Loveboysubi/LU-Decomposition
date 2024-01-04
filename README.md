# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.

2. get input from user and print L and U matrix by 'print'

3.define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in the variable

4. print the variable 'X' 

## Program:
```PYTHON
(i) To find the L and U matrix
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Subishesh P
RegisterNumber:23003621 
'''
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```PYTHON
/*
'''Program to solve a matrix using LU decomposition.
Developed by:Subishesh P
RegisterNumber:23003621
'''
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```



## Output:
![image](https://github.com/Loveboysubi/LU-Decomposition/assets/138970879/8221cdd1-d8cf-44b0-9a7b-7c0339d54c67)
![image](https://github.com/Loveboysubi/LU-Decomposition/assets/138970879/2b94f457-ce1e-4dab-a3c2-3943c77b0441)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

