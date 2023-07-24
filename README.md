# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for L and U Matrix
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu
3. Enter the lists from each linear equations and assign in np.array() 
4. using lu() and store it in three variables
5. print the L and U Matrix 
6. End the program 

## Algorithm for LU Decomposition
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu_factor,lu_solve
3. Enter the lists from each linear equations and assign in np.array()
4. Enter the lists from each linear equations and assign in np.array()
5. using lu_factor() and store it in two variables
6. using lu_solve(),we can find L and U matrix
7. End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:MIDHUN S 
RegisterNumber:23003250 
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:MIDHUN S
RegisterNumber: 23003250
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,plv=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:
![output](/Screenshot%202023-07-23%20232024.jpg)
![output](/Screenshot%202023-07-23%20232308.jpg)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

