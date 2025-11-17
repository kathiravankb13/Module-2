
# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM
```

x=int(input())
y=int(input())
if(x<y):
    print(x,"is smaller than",y)
else:
    print(y,"is smaller than",x)
```

### OUTPUT

<img width="959" height="273" alt="Screenshot 2025-08-31 203706" src="https://github.com/user-attachments/assets/df45d346-21f5-4b3c-b0c8-1cc05c870e64" />


### RESULT
Thus a a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function was executed successfully.
