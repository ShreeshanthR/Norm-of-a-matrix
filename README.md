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
# Register No: 212225040411
# Developed By: Shreeshanth R
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<img width="708" height="237" alt="image" src="https://github.com/user-attachments/assets/a1e5dcc7-36f0-4980-9116-88273bfe1373" />
<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="573" height="272" alt="image" src="https://github.com/user-attachments/assets/08579082-8607-45de-9d59-eac81135222e" />
<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="611" height="217" alt="image" src="https://github.com/user-attachments/assets/5b9657d8-d72a-4b3a-9ea4-cf80f3476c94" />
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
