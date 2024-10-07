### Date : 
# Ex-7 : Norm of a matrix
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
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```
### 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
```
### Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![1)](https://github.com/user-attachments/assets/e8df66b0-cc65-4535-a7c3-478f4cc80436)
### 2-Norm of a Matrix
![2)](https://github.com/user-attachments/assets/ab2b527d-03ee-409f-9e33-c8c2e6cf6c1f)


### Infinity Norm of a Matrix
![3)](https://github.com/user-attachments/assets/c63f73e0-4ca1-4721-a1b8-85d3e5dc71e2)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
