# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1-norm of matrix:
	1. Get the input matrix using np.array()   
        2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
2-norm of matrix:
        1. Get the input matrix using np.array()   
        2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
Infinity norm of matrix:
         1. Get the input matrix using np.array()   
        2. Find the inf-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
         
         
## Program:
```Python
# Register No:UDHAYA PRAKASH V
# Developed By:24901131

# 1-Norm of a Matrix:
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)

# 2-Norm of a Matrix:
'''
Program to find 2-norm of a matrix.
Developed by: udhaya prakash v 
RegisterNumber:24901131 
'''
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(f"{result:.2f}")


# Infinity Norm of a Matrix:
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)





```
## Output:
### 1-Norm of a Matrix:
![ot](https://github.com/user-attachments/assets/ad1008a9-4f50-4552-aacf-2058202f6cbe)


### 2-Norm of a Matrix:
![out 2](https://github.com/user-attachments/assets/7d3168d7-be40-4a70-9aa1-40752ac57115)

### Infinity Norm of a Matrix:

![out 1](https://github.com/user-attachments/assets/d393602c-b742-4364-8a1f-6b528d29e003)




## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
