# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## 5(A):
#5.a.
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3. Using the scipy.linalg.lu(), we can find the solutions.
4. End the program

#5.b
1. Import the numpy module to use the built-in functions for calculation
2.  Prepare the lists from each linear equations and assign in np.array()
3.  Using the scipy.linalg.lu(), we can find the solutions.
4.  Use the lu_factor() function to obtain the LU factorization of A matrix
5.  use the lu_solve() function to solve the system of linear equation
6.  End the program
## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![lu decomposition]()
<img width="1697" height="740" alt="Screenshot 2026-10-14 122413" src="https://github.com/user-attachments/assets/bd55290c-e213-4bae-922e-aea971b068cc" />
<img width="1710" height="575" alt="Screenshot 2026-10-14 122432" src="https://github.com/user-attachments/assets/5af80965-cbcc-4911-a792-869e291da5ad" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

