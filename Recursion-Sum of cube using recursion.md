# 🔁 Recursion:To find the sum of cube of a first n Natural Numbers



## 🎯 AIM:
To write a Python program to find the sum of cubes of the first n natural numbers using recursion.

## 🧠 ALGORITHM:

1.Start the program.

2.Define a recursive function sum(n):

3.If n == 0, return 0 (base case).

4.Otherwise, return n³ + sum(n-1).

5.Read the value of n from the user.

6.Call the function sum(n) and print the result.

7.Stop the program.

## 💻 PROGRAM:
```
def sum(n):
    if n==0:
        return 0
    else:
        return n**3+sum(n-1)
n=int(input())
print("Result is",sum(n))
```

## OUTPUT
<img width="954" height="240" alt="image" src="https://github.com/user-attachments/assets/3ad36088-e2e1-4265-bc26-86735635a424" />

## RESULT

Thus, the program to find the sum of cubes of the first n natural numbers using recursion has been executed successfully.
