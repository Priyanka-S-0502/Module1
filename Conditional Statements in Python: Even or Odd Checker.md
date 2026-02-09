# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
num = int(input())

if num % 11 == 0 and num % 4 == 0:
    print(f"{num} is divisible by both 11 and 4")
else:
    print(f"{num} is NOT divisible by both 11 and 4")

```

## Output
<img width="878" height="202" alt="image" src="https://github.com/user-attachments/assets/5db51347-1e3a-4473-9f3a-850036d5be7f" />


## Result
Thus, the program to check whether a given number is divisible by both 11 and 4 using if-else was executed successfully and the output was verified.
