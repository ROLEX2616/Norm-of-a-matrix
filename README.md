## DATE:
## EX NO: 7-Norm of a matrix
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
# Register No:212223100019
# Developed By:KAVINRAJ.S
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-10-06 183835](https://github.com/user-attachments/assets/b57353fd-f9a7-4111-b25b-ba98ea0b3829)


### 2-Norm of a Matrix
![Screenshot 2024-10-06 183849](https://github.com/user-attachments/assets/ed47748f-0c78-4bd0-b91b-62f8a5e48cb8)

### Infinity Norm of a Matrix
![Screenshot 2024-10-06 183902](https://github.com/user-attachments/assets/6e4676ae-cc9a-44f5-9daa-6cb1a4c72b70)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
