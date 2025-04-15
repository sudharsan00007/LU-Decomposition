# LU Decomposition 

AIM:
To write a program to find the LU Decomposition of a matrix.



Equipments Required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner


Algorithm:


Step 1:
import numpy as np



Step 2:
from scipy package import lu



Step 3:
get input from the user



Step 4:
print result



## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SUDHARSAN S
RegisterNumber: 212224040334
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SUDHARSAN S
RegisterNumber: 212224040335
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)
*/
```

## Output:
![Screenshot 2025-04-15 102950](https://github.com/user-attachments/assets/0c574a09-845f-4cce-83ce-5645c052404e)

![Screenshot 2025-04-15 103003](https://github.com/user-attachments/assets/b1297b38-0c13-4d1c-8816-19bb5ab835f0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

