# Exp.No:3e  
## SEB - STRING SLICING

### AIM  
To write a Python function that accepts a string and forms a new string by extracting **alternate characters** starting from the **3rd character** to the **10th character** (exclusive), and then prints the sliced string.

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Slice the string from index **2** to **10** with a step of **2** to extract every second character.  
   - (Python uses 0-based indexing, so index 2 refers to the 3rd character.)  
4. Store the result in a variable.  
5. Print the final sliced string.  
6. Terminate the program.

### PROGRAM

```
def slice(s):
    a = s[2:10:2]
    print(f"The sliced string is '{a}'")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/17bdda2d-ffa5-42b8-95b4-92b59fa5a4a0)

### RESULT
Thus the program was executed successfully and the string was sliced correctly to extract alternate characters from the 3rd to the 10th position.
