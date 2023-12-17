# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: RAJARAMAN V
RegisterNumber: 23014299
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:  RAJARAMAN V
RegisterNumber: 23014299
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:
![image](https://github.com/Rajaraman77/LU-Decomposition/assets/150319383/261b01c8-951e-4664-a9d1-86c6dc038e49)
![image](https://github.com/Rajaraman77/LU-Decomposition/assets/150319383/748fdefe-51bd-4ed7-8fc8-06e2f1164266)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

