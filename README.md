# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Get the array input from the user
3. Prepare the lists from the given matrix and assign in np.array()
4. Print the L U matrix values

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Reklies J
RegisterNumber: 212223110041

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Reklies J
RegisterNumber: 212223110041


# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor , lu_solve
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
(i) To find the L and U matrix

![Screenshot 2023-12-22 000912](https://github.com/AkilaMohan/LU-Decomposition/assets/147139232/b17cf6d9-2590-4d1d-ac93-98c93d0f999b)



(ii) To find the LU Decomposition of a matrix
![Screenshot 2023-12-22 001026](https://github.com/AkilaMohan/LU-Decomposition/assets/147139232/a3f4636e-2b12-4bd6-b648-1d581b86312a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

