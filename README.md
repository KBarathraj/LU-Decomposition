# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: K Barathraj
RegisterNumber: 24001402

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:K Barathraj 
RegisterNumber: 24001402
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
```

## Output:
![image](https://github.com/user-attachments/assets/f495bd54-1672-43d1-ba89-fd8c3cc3fc2d)
![image](https://github.com/user-attachments/assets/e71eb440-466b-42ab-95e9-2229d9564ade)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

