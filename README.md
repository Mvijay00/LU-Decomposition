# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
```
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SARVESH.M
RegisterNumber: 212225240140

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SARVESH.M
RegisterNumber: 212225240140

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

*/
```

## Output:

<img width="1527" height="791" alt="Screenshot 2026-02-07 082301" src="https://github.com/user-attachments/assets/4317060f-54cd-4925-a4be-a8acf2eaa3c4" />

<img width="1632" height="669" alt="Screenshot 2026-02-07 082316" src="https://github.com/user-attachments/assets/190384e0-04f4-4165-b43e-c1e27bc2b496" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

