# -Broadcasting
24-02-25
8. Broadcasting 
import numpy as np
arr = np.array([1, 2, 3])
scalar_added = arr + 10
arr2D = np.array([[1, 2, 3],  [4, 5, 6]])
arr1D = np.array([10, 20, 30])
broadcast_added = arr2D + arr1D
print("Original 1D Array:", arr)
print("After Adding Scalar (10):", scalar_added)
print("\n2D Array:\n", arr2D)
print("1D Array:", arr1D)
print("After Broadcasting Addition:\n", broadcast_added)
Output:
Original 1D Array: [1 2 3]
After Adding Scalar (10): [11 12 13]
2D Array:
 [[1 2 3]
 [4 5 6]]
1D Array: [10 20 30]
After Broadcasting Addition:
 [[11 22 33]
 [14 25 36]]
