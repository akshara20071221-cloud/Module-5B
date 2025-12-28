# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

# Get input from user
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter the elements:")
arr = np.array([[int(input()) for j in range(cols)] for i in range(rows)])

# Sort column-wise
sorted_arr = np.sort(arr, axis=0)

# Display output
print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)

```

## Output
<img width="537" height="377" alt="image" src="https://github.com/user-attachments/assets/17a8f53d-a91d-4edb-b050-863bfc1040c0" />


## Result
code is executed
