# Exp.No: 3b  
## STRING MATCHING USING REGULAR EXPRESSIONS

### AIM  
To write a Python program to check whether the letter 'z' is present in the given string using regular expressions.

### ALGORITHM

1. Start the program.  
2. Import the `re` module.  
3. Accept a string input from the user and store it in variable `a`.  
4. Use `re.search()` to search for the character `'z'` in the string.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. End the program.

### PROGRAM

```
import re
a = input()
x = re.search("[z]", a)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/9f446ead-802f-4ea9-b8c1-0251ab92377c)

### RESULT
Thus, the Python program successfully uses regular expressions to check for the presence of the letter 'z' in the input string.
