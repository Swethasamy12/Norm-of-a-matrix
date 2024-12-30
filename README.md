# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm for 1 norm matrix:
```
1. Get the input matrix using np.array()
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Algorthim for 2 norm matrix:
```
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Algorthim for infinity norm matrix:
```
1. Get the input matrix using np.array()   
2. Find the Infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No:24901183
# Developed By:Swetha C
```
```
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)

# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-26 060240](https://github.com/user-attachments/assets/7201464e-5abb-4efc-9b7d-3641e7e5416d)


### 2-Norm of a Matrix
![Screenshot 2024-12-26 060258](https://github.com/user-attachments/assets/83c2cad2-abc6-45bf-bb77-cdd9859e2f69)


### Infinity Norm of a Matrix
![Screenshot 2024-12-26 060314](https://github.com/user-attachments/assets/0f824b1f-76a9-4189-a13e-05c52d054c84)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
