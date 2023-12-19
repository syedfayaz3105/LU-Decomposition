# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Farhana H
RegisterNumber:23012987 
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Farhana H
RegisterNumber: 23012987
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
*/
```

## Output:
![image](https://github.com/syedfayaz3105/LU-Decomposition/assets/147144126/3170eec9-1abe-4a62-8c8c-13fe394fe538)
![image](https://github.com/syedfayaz3105/LU-Decomposition/assets/147144126/7931bfb5-fcfd-4408-83a2-6da987cd76b1)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

