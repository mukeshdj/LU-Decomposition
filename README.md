# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
![image](https://github.com/mukeshdj/LU-Decomposition/assets/155506353/9ad07115-53fd-4a75-9dec-d3894438710b)


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MUKESH S
RegisterNumber: 2305002016
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
/*
Program to find the LU Decomposition of a matrix.
Developed by: MUKESH S
RegisterNumber: 2305002016
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/mukeshdj/LU-Decomposition/assets/155506353/ca0756b7-60cd-4ea3-94d8-ff1b7de70f41)
![image](https://github.com/mukeshdj/LU-Decomposition/assets/155506353/5ea827c0-8843-475a-b7f4-ada9590a95eb)
![image](https://github.com/mukeshdj/LU-Decomposition/assets/155506353/2b0cb7ff-e36a-41ad-88dc-8531d253b4d9)
![image](https://github.com/mukeshdj/LU-Decomposition/assets/155506353/5046c196-ab88-49ce-a84b-8abd89e0b1d7)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python
programming.
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

