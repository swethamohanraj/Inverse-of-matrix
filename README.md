# Inverse-of-matrix

## AIM:
To write a program to perform Inversse-of-matrix using python programming.

## ALGORITHM:
### Step 1:
Import Numpy module as np.
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv


## PROGRAM:
```
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range(n1):
    for j in range(n2):
        values=int(input())
        l1.append(values)
    l2.append(l1)
    l1=[]
print(l2)
a=np.linalg.inv(l2)
print(a)
```

## OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/153698638-2b9253ca-b774-446d-8b2d-9bd62a1f5b65.png)

## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.

