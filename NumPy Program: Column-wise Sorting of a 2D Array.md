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

arr = np.array([[3, 1, 2], [6, 5, 4], [9, 7, 8]])
sorted_arr = np.sort(arr, axis=0)
print(sorted_arr)
```
## Output

<img width="302" height="170" alt="{23F2B97A-C726-408B-9C5A-46F1BF1718AF}" src="https://github.com/user-attachments/assets/4bcdd54a-1202-478b-922a-00f389186c03" />
