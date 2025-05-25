# Exp.No:3a
## STRING - String Slicing

## Aim
To create a Python function that accepts a string and prints the characters between positions 2 and 7 of that string.

## Algorithm
1. Begin the program.
2. Define a function `slice()` that:
   - Takes a string as input.
   - Slices the string from position 2 to 6.
   - Prints the sliced substring.
3. Read a string from the user using `input()`.
4. Call the `slice()` function with the input string.
5. Terminate the program.

## Program
```
def slice(input_string):
    sliced_string = input_string[2:7]
    print(f'The sliced string is \'{sliced_string}\'')

n = input()  
slice(n)  
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6f992215-9467-4d7a-b948-6f84fccc8050)

### RESULT
Thus, the Python program was successfully executed to slice a string and print the characters between positions 2 and 7.
