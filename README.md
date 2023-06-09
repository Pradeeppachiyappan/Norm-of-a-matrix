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
### 1-Norm of a Matrix
```
'''
Program to find 1-norm of a matrix.
Developed by: P.Pradeep Raj
RegisterNumber: 212222240073
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
```
### 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: P.Pradeep Raj
RegisterNumber: 212222240073
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
```
### Infinity Norm of a Matrix
```
'''
Program to find norm of a matrix.
Developed by: P.Pradeep Raj
RegisterNumber: 212222240073
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix
![Screenshot (86)](https://github.com/Pradeeppachiyappan/Norm-of-a-matrix/assets/118707347/7ffac17a-a61f-4903-9ccf-38bb35b96186)
### 2-Norm of a Matrix
![Screenshot (87)](https://github.com/Pradeeppachiyappan/Norm-of-a-matrix/assets/118707347/d7171553-f0a7-490c-9a4b-4aaaf1d5ef1f)
### 3-Infinity Norm of a Matrix
![Screenshot (88)](https://github.com/Pradeeppachiyappan/Norm-of-a-matrix/assets/118707347/a1834e20-da2e-453e-a24f-3c840189b8d3)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
