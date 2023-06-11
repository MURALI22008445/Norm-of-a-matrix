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
# Developed By:MURALI S 
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
### 1-Norm of a Matrix
![AI 7A](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/ec1a671c-a83a-4f99-ab93-83de617370c9)

### 2-Norm of a Matrix

![AI 7 B](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/12c28c44-2055-4b0c-ad18-e3e179901f34)

### Infinity Norm of a Matrix
![AI 7 C](https://github.com/MURALI22008445/Norm-of-a-matrix/assets/119643767/7539119a-9aad-490e-bda4-f6a89a2734ab)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
