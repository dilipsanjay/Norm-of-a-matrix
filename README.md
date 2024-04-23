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

# 1-Norm of a Matrix
```
#devoloped by Dilip sanjay
#register no. 212223240032
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Dilip sanjay M
RegisterNumber: 212223240032
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```



# Infinity Norm of a Matrix
```
#devoloped by Dilip sanjay M
#register number 212223240032
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))
```




## Output:
### 1-Norm of a Matrix
![image](https://github.com/dilipsanjay/Norm-of-a-matrix/assets/155506948/34332ed8-d20b-4a6f-9810-da2ca26a51d5)

### 2-Norm of a Matrix
![image](https://github.com/dilipsanjay/Norm-of-a-matrix/assets/155506948/83c8fc89-1350-47d8-b20b-a61783064ef3)


### Infinity Norm of a Matrix
![image](https://github.com/dilipsanjay/Norm-of-a-matrix/assets/155506948/de489434-2da0-453b-af23-15fd61ad4fb7)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
