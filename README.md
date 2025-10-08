# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program

2.Import the necessary libraries(numpy,scipy.linalg)

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program.  

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Jeevanantham C
RegisterNumber: 25013725 
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Jeevanantham C
RegisterNumber: 25013725
'''

# To print X matrix (solution to the equation)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) <img width="1248" height="577" alt="Screenshot 2025-10-08 142722" src="https://github.com/user-attachments/assets/371bde4f-ec1d-4795-bc2a-02a09079047b" />
(ii) <img width="1236" height="317" alt="Screenshot 2025-10-08 142806" src="https://github.com/user-attachments/assets/587873cf-0699-40d9-ac5e-d2129c23206d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

