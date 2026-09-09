# Norm of a matrix
## Aim:

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
# Register No:212225230263
# Developed By:sherlin jenifa vs
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```



# 2-Norm of a Matrix


Program to find 2-norm of a matrix.
Developed by: Sherlin Jenifa VS
RegisterNumber: 212225230263
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

<img width="948" height="808" alt="image" src="https://github.com/user-attachments/assets/93abfaa8-1d88-4bbb-ab70-9933ea96dd4f" />

### 2-Norm of a Matrix

<img width="992" height="827" alt="image" src="https://github.com/user-attachments/assets/1b1b4e81-a3c6-479a-91d1-d6a39b5324d9" />


### Infinity Norm of a Matrix

<img width="741" height="767" alt="image" src="https://github.com/user-attachments/assets/d01f92c7-b665-4640-af5e-293018778dbc" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
