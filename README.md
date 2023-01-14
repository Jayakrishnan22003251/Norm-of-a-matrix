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
# Register No: 22003251
# Developed By: JAYAKRISHNAN L B L
# 1-Norm of a Matrix
        import numpy as np
        a=np.array(eval(input()))
        b=np.linalg.norm(a,1)
        norm1='{:.2f}'.format(b)
        print(norm1)



# 2-Norm of a Matrix
        import numpy as np
        a=np.array(eval(input()))
        b=np.linalg.norm(a,2)
        c='{:.2f}'.format(b)
        print(c)


# Infinity Norm of a Matrix
        import numpy as np
        a=np.array(eval(input()))
        b=np.linalg.norm(a,np.inf)
        c='{:.2f}'.format(b)
        print(c)


```
## Output:
### 1-Norm of a Matrix
        ![image (11)](https://user-images.githubusercontent.com/120232371/212464310-9b4a0e2d-5ee8-4daf-ad39-5016802d432a.png)

### 2-Norm of a Matrix
        ![image (12)](https://user-images.githubusercontent.com/120232371/212464445-76001930-ff86-4840-9722-6d15bb039f71.png)


### Infinity Norm of a Matrix
       ![image (13)](https://user-images.githubusercontent.com/120232371/212464474-d8a6aeba-e88d-4d7a-959c-7253b2f893f1.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
