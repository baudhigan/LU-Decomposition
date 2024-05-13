# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Read the elements of augmented matrix into arrays a and b
2. Calculate elements of L and U
3. Print elements of L and U
4. Find V by solving LV = B by forward substitution
5. Find X by solving UX = V by backward substitution
6. Print Array X as the solution

## Program:
(i) To find the L and U matrix

##Program to find the L and U matrix.

##Developed by: BAUDHIGAN D

##RegisterNumber: 212223230028

```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix

##Program to find the LU Decomposition of a matrix.

##Developed by: BAUDHIGAN D

##RegisterNumber: 212223230028

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
```

## Output:
![Screenshot 2024-05-13 071547](https://github.com/baudhigan/LU-Decomposition/assets/151921158/331fd4da-6094-473e-8482-e81904eec283)


### LU Decomposition
![Screenshot 2024-05-13 071604](https://github.com/baudhigan/LU-Decomposition/assets/151921158/742ad177-f157-4444-89f5-d75f9bdaaa84)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

