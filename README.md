# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : Start and input the order and elements of the square matrix.

### step 2. Calculate the determinant of the matrix. If the determinant is zero, display “Inverse does not exist”.

### step 3. If the determinant is non-zero, find the inverse using matrix operations/formula.

### step 4. Display the inverse matrix and stop.

## Program:
#Program to find the inverse of a matrix.

#Developed by: Bristo AK

#RegisterNumber:212225230037
```
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse = np.linalg.inv(matrix)
print(inverse)
```
## Output:
<img width="1230" height="209" alt="Screenshot 2026-05-14 105818" src="https://github.com/user-attachments/assets/aa155bce-8469-439b-b1ef-13b45b89b31b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

