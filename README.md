# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program
```
#Program to find the rank of a matrix.
#Developed by :G.DHARNISH
#RegisterNumber: 25004380
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
x = np.array([[3,2,5],[1,1,2],[3,3,6]])
y = np.linalg.matrix_rank(x)
print(y)
```


## Output:

<img width="825" height="804" alt="image" src="https://github.com/user-attachments/assets/f1f7c2f6-6b4c-412c-8462-d5ca05e28854" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

