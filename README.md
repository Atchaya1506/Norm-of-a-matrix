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
```
Python
# Register No:212224220015
# Developed By:ATCHAYA B
# Register No:21224230214
```
```
 #1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix

<img width="1255" height="773" alt="image" src="https://github.com/user-attachments/assets/afb7dfee-16ea-4c43-862e-ea5c3010ae22" />

### 2-Norm of a Matrix

<img width="1375" height="779" alt="image" src="https://github.com/user-attachments/assets/523c1277-c613-470f-800e-11202b7d86d6" />


### 3-Infinity Norm of a Matrix

<img width="1353" height="790" alt="image" src="https://github.com/user-attachments/assets/99eb8843-681c-45c0-93ed-83a9f625beec" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
