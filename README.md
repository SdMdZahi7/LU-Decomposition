# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 1. To Find L and U matrices with LU Decomposition
Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu" to import scipy (LU) module.

Step 3: Using "L,U=lu(a)" we can get the matrix of L and U.

Step 4: Print the result matrices (L and U Matrices).

Step 5: End of the Program.


### 2. To Find X matrix with LU Decomposition
Step 1: Get the matrix from the user.

Step 2: Using "from scipy.linalg import lu_factor,lu_solve" to import scipy module for factorization and solving X.

Step 3: Using "lu,piv=lu_factor(a)" 

Step 4: Print result matrix (X Matrix)

Step 5: End of the Program.

## Program:
(i) To find the L and U matrix
```
/*
Developed by:Syed Muhammed Zahi 
RegisterNumber:21004029

# To print L and U matrix
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
Developed by:Syed Muhammed Zahi
RegisterNumber:21004029

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv= lu_factor(A)
x = lu_solve((lu,piv),B)
print(x) 
*/
```

## Output:
(i):
![lu dec](https://user-images.githubusercontent.com/94187572/147854196-71ddeeae-67d1-413a-a15d-6b2aade6cb21.png)


(ii):

![lu dec2](https://user-images.githubusercontent.com/94187572/147854239-6b581531-afc5-412f-8e22-6e99d1d13d0d.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

