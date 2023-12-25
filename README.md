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
# Register No: 23003227
# Developed By: R Anirudh
# 1-Norm of a Matrix

import numpy as np
a =np.array(eval(input()))
b=np.linalg.norm(a,1)
norm_of_matrix = "{:.2f}".format(b)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
norm_of_matrix='{:.2f}'.format(b)
print(norm_of_matrix)





# Infinity Norm of a Matrix


import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
norm_of_matrix="{:.2f}".format(b)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot (28)](https://github.com/anushanirudh/Norm-of-a-matrix/assets/151725737/6dce64d8-db31-46c7-9102-ec35c07886f1)


### 2-Norm of a Matrix
![Screenshot (30)](https://github.com/anushanirudh/Norm-of-a-matrix/assets/151725737/5ab08b6f-6441-4890-bf4b-956079036354)


### Infinity Norm of a Matrix
![Screenshot (29)](https://github.com/anushanirudh/Norm-of-a-matrix/assets/151725737/f3345755-89aa-4327-9c65-79ca974a41f2)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
