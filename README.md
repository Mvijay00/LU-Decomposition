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
Developed by: VIJAYARAGHAVAN
RegisterNumber: 212225100058

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
Developed by: VIJAYARAGHAVAN
RegisterNumber: 212225100058

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
<img width="1283" height="861" alt="Screenshot 2026-03-24 143606" src="https://github.com/user-attachments/assets/2933e954-3101-4a47-8b12-10ee0182d871" />


<img width="934" height="691" alt="Screenshot 2026-03-24 080240" src="https://github.com/user-attachments/assets/4891ad9b-a290-4c31-91ba-302351103de4" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

