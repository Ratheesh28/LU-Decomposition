# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1
Define the package as scipy.linalg import lu.
Step 2
Get input from user and print L and U matrix by 'print' .
Step 3
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
Step 4
print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Ratheesh Kumar B R 
RegisterNumber: 212223110040
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Ratheesh Kumar B R
RegisterNumber: 212223110040
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2024-04-25 080753](https://github.com/Ratheesh28/LU-Decomposition/assets/138849186/3aa429da-14d3-4099-bacc-9e93fec72e20)
![Screenshot 2024-04-25 080827](https://github.com/Ratheesh28/LU-Decomposition/assets/138849186/ac45072f-50e2-4a04-b2ee-2c3c9b56c8b9)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

