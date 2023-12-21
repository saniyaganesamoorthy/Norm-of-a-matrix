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
# Register No:  212223240147
# Developed By: SANIYA G

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![1](https://github.com/saniyaganesamoorthy/Norm-of-a-matrix/assets/145742583/df2bae94-181d-436f-bd8f-dcf84bf6257d)

### 2-Norm of a Matrix
![2](https://github.com/saniyaganesamoorthy/Norm-of-a-matrix/assets/145742583/d5c243fc-7b22-4ea8-9300-b97e7506b04a)

### Infinity Norm of a Matrix
![3](https://github.com/saniyaganesamoorthy/Norm-of-a-matrix/assets/145742583/415b48ba-0288-4ffa-92e4-a31dc18fef55)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
