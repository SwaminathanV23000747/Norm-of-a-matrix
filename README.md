# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:Swaminathan V
# Developed By:23000747
# 1-Norm of a Matrix
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: Swaminathan V
RegisterNumber: 23000747

import numpy as np

# Type your code here

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

Program to find Infinity norm of a matrix.
Developed by: Swaminathan V
RegisterNumber: 23000747

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![7 ss1](https://github.com/SwaminathanV23000747/Norm-of-a-matrix/assets/148931113/cd7bf869-1e32-423f-a537-dca5083155e4)

### 2-Norm of a Matrix
![7 ss2](https://github.com/SwaminathanV23000747/Norm-of-a-matrix/assets/148931113/b86c259d-d63b-4690-a2cc-15318c58d249)

### Infinity Norm of a Matrix
![7 ss3](https://github.com/SwaminathanV23000747/Norm-of-a-matrix/assets/148931113/035ab0f9-4eec-402d-bbcb-d55737ae6bdb)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
