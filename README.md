# day3
ANS1.
np.arange(2,50).reshape(2,8,3)
array([[[ 2,  3,  4],
        [ 5,  6,  7],
        [ 8,  9, 10],
        [11, 12, 13],
        [14, 15, 16],
        [17, 18, 19],
        [20, 21, 22],
        [23, 24, 25]],

       [[26, 27, 28],
        [29, 30, 31],
        [32, 33, 34],
        [35, 36, 37],
        [38, 39, 40],
        [41, 42, 43],
        [44, 45, 46],
        [47, 48, 49]]])

ANS 2.
l=[]
for i in range(5):
    i=input(" Please enter elemnet of list1: ")
    l.append(i)
l2=[]
for j in range(5):
    j=input(" Please enter elemnet of list2: ")
    l2.append(j)
l=np.array()
l2=np.array()
print(l)
print(l2)
print(l+l2)

Ans3.
arr = np.array([[[1, 2, 3], [4, 5, 6]], [[1, 2, 3], [4, 5, 6]]])

print(arr.ndim)
print(arr.size)

ANS 4.
arr = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12])

newarr = arr.reshape(4, 3)

print(newarr)

Ans 5.
import matplotlib.pyplot as plt
import numpy as np

xpoints = np.array([0, 6])
ypoints = np.array([0, 250])

plt.plot(xpoints, ypoints)
plt.show()
