# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Get the input matrix using np.array()   
Step 2: Find the 2-norm of the matrix using np.linalg.norm()
Step 3: Print the norm of the matrix in two decimal places.
Step 4: End the program.

	
## Program:
```Python

# 1-Norm of a Matrix
'''
Developed by : Ashwin kumar E
Registration Number : 212224230026
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm1 = np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by:Ashwin kumar E
RegisterNumber: 212224230026
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
result = np.linalg.norm(arr,2)
print("{:.2f}".format(result))



# Infinity Norm of a Matrix

'''
Developed by :Ashwin kumar E
Register Number : 212224230026
'''
import numpy as np
matrix = eval(input())
arr = np.array(matrix)
result = np.linalg.norm(arr,np.inf)
print("{:.2f}".format(result))



```
## Output:
### 1-Norm of a Matrix
<img width="900" height="332" alt="Screenshot 2025-10-17 195015" src="https://github.com/user-attachments/assets/e88767bd-b3a9-4a8b-9c95-cc534f3d4f4b" />

## 2-Norm of a Matrix
<img width="898" height="302" alt="Screenshot 2025-10-17 195028" src="https://github.com/user-attachments/assets/38f7ada8-dd00-4d62-9430-961a031af83b" />

## Infinity Norm of a Matrix
<img width="1027" height="296" alt="Screenshot 2025-10-17 195042" src="https://github.com/user-attachments/assets/2701f97b-cdb1-4301-8b6d-d61dd68ebcf1" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
