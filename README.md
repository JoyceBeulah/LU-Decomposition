# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and scipy packages
2. Read the input matrix as two dimensional array
3. Call the Built in function lu() to decompose the array
4. print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: R.Joyce Beulah
RegisterNumber: 22009334
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: R. Joyce Beulah
RegisterNumber: 22009334
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![find L and U](/lu%20output.png)
![LU decomposition](/lu%20output2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

