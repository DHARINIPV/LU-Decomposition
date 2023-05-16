# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. Import library called 'scipy' to solve the lu decomposition.
3. Import lu_factor and lu_solve libraries.
4. Get the input to solve the lu decomposition.
5. Print the result obtained.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Dharini PV
RegisterNumber: 212222240024
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Dharini PV
RegisterNumber: 212222240024
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = eval(input()) #np.array(eval(input()))
B = eval(input())
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)

```

## Output:

![Screenshot 2023-05-16 091752](https://github.com/DHARINIPV/LU-Decomposition/assets/119400845/d1f10994-55bd-4e44-871b-f37d8fe36438)

![Screenshot 2023-05-16 093217](https://github.com/DHARINIPV/LU-Decomposition/assets/119400845/fb43bc00-57f7-4da1-8121-4acb65d0a6e9)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

