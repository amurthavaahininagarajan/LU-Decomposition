# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import maths as numpy
2. give the input values
3. use eval input
4. print the L and U matrix

## Program:
(i) To find the L and U matrix
```python
/*
Program to find the L and U matrix.
Developed by: AMURTHA VAAHINI KN
RegisterNumber: 22009070
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```python
/*
Program to find the LU Decomposition of a matrix.
Developed by: AMURTHA VAAHINI KN
RegisterNumber: 22009070
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
x=lu_solve((lu,piv),B)
print(x) 
*/
```

## Output:
![](lu2.png)
![](lu1.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

