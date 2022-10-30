# Day6-Lab1-NumPy


import numpy as np


## Q#1: Create x array with elements equal to 1.

x = np.ones([3,6])
x


## Q#2: Create y array with elements equal to 0.

y = np.zeros([1,4])
y


## Q#3: Add x and y arrays.

x+y

## Q#4: Print x array characteristics (e.g: dimension, shape, size, type)


dimensions = x.ndim
print('The dimensions= ', dimensions)

shape= x.shape
print('The shape= ', shape)

size = x.size
print('The size= ',size)

typee = x.dtype
print('The type=', typee)


## Q#5: Create a 2D array "called w" as the following:
w = np.array ([[11,12], [13,14], [15,16]])
w
——
w = np.array([11,12,13,14,15,16])
w.reshape(3,2)


## Q#6: Create z array contains the numbers from 1 to 3.

z= np.arange(1,4)
z

## Q#7: Combine the arrays z and w in vertical way then save it in a new variable "newArray".

newArray= np.column_stack((z,w))
newArray


## Q#8: Print all elements of "newArray" using the loop.

for row in newArray:
    for item in row:
        print(item)


## Q#9: Reverse the columns and rows of "newArray".

newArray.transpose()


## Q#10: Decrement all elements of "newArray" with 1.

newArray-=1
newArray

## Q#11: Find smallest and biggest values in "newArray".

newArray.min()
newArray.max()


## Q#12: Print the first row of "newArray" using indexing.

newArray[0]


## Q#13: Print the number equals 12 of "newArray" using indexing.

newArray[0,2]

## Q#14: Print the numbers equal 0 and 13 of "newArray" using Slicing.

numpy.where(condition, [x, y, ]/)



## Q#15: Change the shape of "newArray" to (9,1).

newArray.reshape(9,1)


## Q#16: Change the shape of "newArray" to (3,2).














