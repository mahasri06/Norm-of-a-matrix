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
# Register No: 212223100029
# Developed By: Mahasri P
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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
![image](https://github.com/mahasri06/Norm-of-a-matrix/assets/139841897/b2283439-f28e-4718-93dc-64b49385f0e0)

### 2-Norm of a Matrix
![image](https://github.com/mahasri06/Norm-of-a-matrix/assets/139841897/37fc36d3-c79b-4a63-b48c-5fa94c2daeab)

### Infinity Norm of a Matrix
![image](https://github.com/mahasri06/Norm-of-a-matrix/assets/139841897/d593fe12-baa6-4d52-95d5-9ed6008a882e)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
