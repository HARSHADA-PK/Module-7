# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by  printing the even number.

## 🧠 ALGORITHM:

1.Start the program.

2.Define a recursive function even(n).

3.If n == 0, return (base condition).

4.Call the function recursively with even(n-1).

5.After returning from recursion, check if n is even (n % 2 == 0).

6.If true, print n.

7.Read the input value of n from the user.

8.Call the function even(n).

9.Stop the program.

## 💻 PROGRAM:
```
def even(n):
    if n==0:
        return
    even(n-1)
    if n%2==0:
        print(n,end=" ")
n=int(input())
even(n)
```

## OUTPUT
<img width="1027" height="270" alt="image" src="https://github.com/user-attachments/assets/4b79b245-6a38-4373-b1fa-eaddb61fd329" />


## RESULT
Thus, the program demonstrates how to print all even numbers from 1 to n using a recursive function and has been executed successfully.
