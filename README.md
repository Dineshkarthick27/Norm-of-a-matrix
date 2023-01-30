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
# Register No:22005847
# Developed By:Dinesh Karthick.K.J
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))




# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot_20230129_194244](https://user-images.githubusercontent.com/120552008/215332270-0ec7d01a-f01a-4c3b-996b-97ed891205a3.png)


### 2-Norm of a Matrix
<br>![Screenshot_20230129_194252](https://user-images.githubusercontent.com/120552008/215332251-17a8bd90-7b3f-4f9c-96e6-0f3bfc2fb4c0.png)


### Infinity Norm of a Matrix
<br>![Screenshot_20230129_194233](https://user-images.githubusercontent.com/120552008/215332285-eb020638-57e5-4f1b-b3db-b5c863ea9c74.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
