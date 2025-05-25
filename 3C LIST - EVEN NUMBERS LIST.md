# Exp.No: 3c
## SUM OF ELEMENTS IN A LIST

### AIM  
To write a Python function to return the sum of all the numbers in a given list.

### ALGORITHM

1. Start the program.  
2. Define a function `sum_list(items)` that takes a list of numbers as input.  
3. Initialize a variable `sum_numbers` to 0.  
4. Iterate through each element `x` in the list and add it to `sum_numbers`.  
5. Return `sum_numbers`.  
6. Call the function with a sample list and print the result.  
7. End the program.

### PROGRAM

```
def sum_list(items):
    sum_numbers = 0
    for x in items:
        sum_numbers += x
    return sum_numbers

print(sum_list([1, 2, -8]))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/58b2b566-7f6c-4426-8b6b-731ea293c29c)

### RESULT
Thus, the Python program successfully computes the sum of all elements in a given list and returns the result.
