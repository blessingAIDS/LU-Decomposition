# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Blessing S
RegisterNumber: 212224230039
*/
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
Developed by: Blessing S
RegisterNumber: 212224230039
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)
```

## Output:
![lu decomposition]()

![Screenshot 2025-04-15 102614](https://github.com/user-attachments/assets/a59c803a-2829-4af3-bc58-b0fa9b7b370a)

![Screenshot 2025-04-15 102831](https://github.com/user-attachments/assets/f3a5aa0c-cb15-4054-940f-48cd0956e8fb)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

