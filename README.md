# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
program-1

1. Get the input matrix using np.array()   

2. Find the 1-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.

program-2

1.Get the input matrix using np.array()

2.Find the 2-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.

program-3

1.Get the input matrix using np.array()

2.Find the infinity-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 24013673
# Developed By:Anbudurai A
```
# 1-Norm of a Matrix
```
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```


# 2-Norm of a Matrix
```
import numpy as np
mat=(eval(input()))
ah=np.linalg.norm(mat,2)
print(f"{ah:.2f}")
```



# Infinity Norm of a Matrix
```
import numpy as np
a=eval(input())
ar=np.array(a)
ah=np.linalg.norm(ar,np.inf)
print(ah)
```
## Output:
### 1-Norm of a Matrix
![alt text](image.png)

### 2-Norm of a Matrix
![alt text](<Screenshot 2024-12-26 141054.png>)

### Infinity Norm of a Matrix
![alt text](image-2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
