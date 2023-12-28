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
Developed by:MOHAMED SULTHAN A
RegisterNumber:23004839

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: MOHAMED SULTHAN A
RegisterNumber: 23004839

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))





# Infinity Norm of a Matrix
Developed by:MOHAMED SULTHAN A
RegisterNumber:23004839

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Sulthan06042007/Norm-of-a-matrix/assets/144980103/30b91fed-0e2f-4418-836b-b1387624c98f)


### 2-Norm of a Matrix
![image](https://github.com/Sulthan06042007/Norm-of-a-matrix/assets/144980103/1389004d-47fb-4f59-ba91-bc86c228e946)


### Infinity Norm of a Matrix
![image](https://github.com/Sulthan06042007/Norm-of-a-matrix/assets/144980103/42223d44-3571-413c-9e08-946f3921385e)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
