# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To create a Python program for printing `n` natural numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```

n=int(input())

for i in range(n,0,-1):
    if i%2!=0:
        print(i)
```
### OUTPUT
![Module 2B](https://github.com/user-attachments/assets/3852e53a-0b6d-419b-9202-fd62d894b4d6)

### RESULT
```
This program for  1 to n Odd numbers in reverse order is successfully executed.

```
