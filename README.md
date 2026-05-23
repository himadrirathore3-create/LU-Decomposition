# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: HIMADRI S
RegisterNumber: 212225040128*/

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='float')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix

```
/*
Program to find the LU Decomposition of a matrix.
Developed by: HIMADRI S
RegisterNumber: 212225040128
*/
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![lu decomposition]()
<img width="1210" height="615" alt="image" src="https://github.com/user-attachments/assets/420616ea-b1ff-4b7e-91ee-2cca64ba9fbc" />
<img width="1217" height="341" alt="image" src="https://github.com/user-attachments/assets/97cb0724-426d-4ec9-a55a-4132f23d6b76" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

