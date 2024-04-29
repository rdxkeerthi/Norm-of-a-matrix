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
# Register No:KEERTHIVASAN M
# Developed By :212223100021
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-29 194635](https://github.com/rdxkeerthi/Norm-of-a-matrix/assets/147473120/07371335-e051-4b16-abdc-f6266e1ba748)


### 2-Norm of a Matrix
![Screenshot 2024-04-29 194653](https://github.com/rdxkeerthi/Norm-of-a-matrix/assets/147473120/3f87b39d-20e9-4493-af7f-95c03ed1732d)


### Infinity Norm of a Matrix

![Screenshot 2024-04-29 194712](https://github.com/rdxkeerthi/Norm-of-a-matrix/assets/147473120/04d1096f-8567-4146-957f-82b2f87d5a23)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
