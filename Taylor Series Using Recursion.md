# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:
```
def power(x, n):
    if n == 0:
        return 1
    else:
        return (x**n)/n+ power(x, n - 1)

x = float(input())
n = int(input())
result =power(x, n)
print(result)
```
## OUTPUT
<img width="546" height="231" alt="image" src="https://github.com/user-attachments/assets/91a8c0d0-b32b-4041-a085-6e3df3902f51" />

## RESULT
Thus,the program is executed successfully
