# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

x = np.array([1, 2, 3, 4, 5])
y = np.array([2, 2, 1, 4, 6])

indices = np.where(x >= y)
print(indices)
```
## Output

<img width="339" height="118" alt="{8DBB8F7E-3EC4-4F6F-B6F0-1C2A83A3107B}" src="https://github.com/user-attachments/assets/d4bb15ca-1caf-4f30-b67a-914d3e1ea8f3" />
