
# Python for Data Analysis – Pandas & NumPy 📊🐍

This repository is a collection of **hands-on mini challenges and solutions** designed to strengthen your skills in **NumPy** and **Pandas**.
Each challenge is crafted to practice data manipulation, array operations, and analytical thinking. 🚀

## 📝 Example Challenge

### MINI CHALLENGE #1

**Task:** Create the following 2x4 NumPy array:

```
[[3 7 9 3]  
 [4 3 2 2]]
```

**Solution:**

```python
import numpy as np

x = np.array([[3, 7, 9, 3], 
              [4, 3, 2, 2]])

print(x)

**Output:**

[[3 7 9 3]
 [4 3 2 2]]

**Task:**
Write a code that takes a positive integer **x** from the user and creates a **1x10 array** with random numbers ranging from **0 to x**.

**Solution:**

```python
import numpy as np

# Take input from user
x = int(input("Enter a positive integer: "))

# Create 1x10 array with random numbers between 0 and x
arr = np.random.randint(0, x+1, size=(1, 10))

print("Generated array:", arr)

