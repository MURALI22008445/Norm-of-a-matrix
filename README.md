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
# Register No:212222230088
# Developed By: MURALI S 
# 1-Norm of a Matrix
```
'''
Programn to find 1-norm of a matrix
Developed by: murali
RegisterNumber: 2122222230088
'''
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: murali
RegisterNumber: 212222230088
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```



# Infinity Norm of a Matrix
```
'''
Program to find the Infinity of a matrix and the result in two decimal places...
Developed by: murali
Register:212222230088
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
![03](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/9daf6f76-c441-4661-80ca-0dd49ff306ca)

![02](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/6b70b947-1b28-45dc-a484-499da4db4ef7)
![01](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/6b54ae47-e65e-4a04-809d-4e6b8b9753bb)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
