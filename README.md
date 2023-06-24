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
# Register No: 212222240083
# Developed By: rohit g
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)




# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
soln=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(soln)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br>![image](https://github.com/rohitgunasekaran/Norm-of-a-matrix/assets/119404546/89e69005-d051-4455-92b8-efbd6e6ba3cf)

<br>
<br>

### 2-Norm of a Matrix
<br>![image](https://github.com/rohitgunasekaran/Norm-of-a-matrix/assets/119404546/f5ed18c7-1459-4bbf-9337-960a2906efa4)

<br> 

<br>

### Infinity Norm of a Matrix
<br> ![image](https://github.com/rohitgunasekaran/Norm-of-a-matrix/assets/119404546/d4a83683-6b5d-477e-8cbe-53e580d8a302)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
