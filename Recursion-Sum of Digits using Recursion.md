# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
```
def func(n):
    if n==0:
        return 0
    else:
        m=n%10
        return m+func(n//10)
n=int(input())
print(func(n))
```
## OUTPUT
<img width="457" height="265" alt="image" src="https://github.com/user-attachments/assets/2e3d9fab-3923-4f71-b2d6-40a4ad0d1b18" />

## RESULT
Thus,the program is executed successfully
