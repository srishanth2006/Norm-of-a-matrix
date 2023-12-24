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
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: yourname SRISHANTH J
RegisterNumber: 212223240160
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix

import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

<img width="656" alt="Screenshot 2023-12-24 195532" src="https://github.com/srishanth2006/Norm-of-a-matrix/assets/150319470/15d51d36-3803-4787-8750-7d3e70fa3dc1">

### 2-Norm of a Matrix

<img width="664" alt="Screenshot 2023-12-24 195552" src="https://github.com/srishanth2006/Norm-of-a-matrix/assets/150319470/35ccb96d-8b5e-417a-b101-b47a018f55f0">

### Infinity Norm of a Matrix
<img width="661" alt="Screenshot 2023-12-24 195603" src="https://github.com/srishanth2006/Norm-of-a-matrix/assets/150319470/6b42c4ad-5cf4-4342-8f8a-4120f54d9388">

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
