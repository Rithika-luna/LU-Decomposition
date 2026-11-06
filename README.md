# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Start the program.

### Step 2: 
Import the required libraries, NumPy and SciPy, using import numpy as np and from scipy.linalg import lu.

### Step 3: 
Create a square matrix using the np.array() function with the required elements.

### Step 4: 
Use the lu() function to decompose the given matrix into three matrices: Permutation matrix (P), Lower triangular matrix (L) and Upper triangular matrix (U).

### Step 5:
Display the original matrix and the P, L and U matrices using the print() statement.

### Step 6:
Stop the program

## Program:
(i) To find the L and U matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)

```

/*
Program to find the L and U matrix.
Developed by: S Rithika 
RegisterNumber: 212225040344
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S Rithika 
RegisterNumber: 212225040344
*/
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
Program to find the L and U matrix.
<img width="1456" height="820" alt="image" src="https://github.com/user-attachments/assets/9b19a669-7253-41b6-8116-a46f2cfa1282" />

Program to find the LU Decomposition of a matrix.

<img width="1436" height="825" alt="image" src="https://github.com/user-attachments/assets/55ba3f25-2c07-4287-ad5a-54647c5ea90c" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

