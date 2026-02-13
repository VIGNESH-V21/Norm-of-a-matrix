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
# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by : VIGNESH V
Register number: 212224040357
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: VIGNESH 
RegisterNumber: 212224040357 
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# Infinity Norm of a Matrix

'''
Program to find Infinity norm of a matrix.
Developed by: VIGNESH 
RegisterNumber: 212224040357
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix

<img width="1270" height="909" alt="image" src="https://github.com/user-attachments/assets/57a18ccc-553d-4820-a963-2b03e61b83da" />


### 2-Norm of a Matrix

<img width="1269" height="981" alt="image" src="https://github.com/user-attachments/assets/a0ed2d0b-cb76-49dc-85dc-86466cd9220d" />


### Infinity Norm of a Matrix

<img width="1295" height="962" alt="image" src="https://github.com/user-attachments/assets/d787a0f0-0a51-4380-b7a0-fe02398d7d8a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
