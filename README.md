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
# Register No: 212223110059
# Developed By:THEJASWINI
# 1-Norm of a Matrix
'''
program to find 1-norm of matrix.
Developed by: THEJASWINI
RegisterNumber : 212223110059
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: THEJASWINI
RegisterNumber: 212223110059
'''
import numpy as np

# Type your code here
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
'''
Program to find Infinity norm of a matrix.
Developed by: THEJASWINI
RegisterNumber: 212223110059
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/thejaswinidhanaraj/Norm-of-a-matrix/assets/148514511/30044a61-74ca-4a35-a1f7-7e67dbe5e81b)
<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/thejaswinidhanaraj/Norm-of-a-matrix/assets/148514511/58695391-5b09-46ea-be03-8b9f173864ec)
<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/thejaswinidhanaraj/Norm-of-a-matrix/assets/148514511/36457c13-4f27-4177-b0f3-71bf19790d4f)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
