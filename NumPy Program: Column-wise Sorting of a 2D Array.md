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
x=np.array(eval(input()))
sorted=np.sort(x,axis=1)
print("Given array ")
print("",x,"\n")
print(sorted)


```

## Output

<img width="1046" height="630" alt="547469648-b98a6102-7e90-49ca-855d-2480e298f65b" src="https://github.com/user-attachments/assets/18171efa-7e0f-4949-89df-f0c2e69da9eb" />



## Result

Thus, the program was executed successfully.
