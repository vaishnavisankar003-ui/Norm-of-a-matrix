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
# Register No:212225230289
# Developed By:vaishnavi s
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))



```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-03-23 221857" src="https://github.com/user-attachments/assets/34f905f1-6cb2-4b4b-a319-f9ffee3d0736" />


### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2026-03-23 221912" src="https://github.com/user-attachments/assets/f199a8bd-3e59-4799-95ae-0204a9dd55ab" />


### Infinity Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot 2026-03-23 221930" src="https://github.com/user-attachments/assets/5a3580a1-c877-4e5c-a7f8-be177a76f8cc" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
