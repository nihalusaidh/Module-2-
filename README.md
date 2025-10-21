
1. Built-in Functions-Binary Conversion
# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

a=16
print(bin(a))
## Output
<img width="1918" height="793" alt="m2 o1" src="https://github.com/user-attachments/assets/6f3e5c8d-2ff3-4efb-a532-f6e93c68f3b5" />


## Result
Thus the conversion of number to binary is executed successfully


2. Functions_ Modulo Calculator
# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
def result(a,b):
    c=a%b
    print(c)
a=int(input())
b=int(input())
result(a,b)

## Output
<img width="1918" height="794" alt="m2 o2" src="https://github.com/user-attachments/assets/7acb7e0d-aa23-4288-a4bc-49ab7d43498f" />


## Result
Thus the program to find the modulo calculator is executed successfully


3. Lambda Function_ Addition of Two Numbers
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))

## Output
<img width="1919" height="790" alt="m2 o3" src="https://github.com/user-attachments/assets/79303e8e-481d-4b02-95e8-259a41ee93de" />


## Result
Thus the lambda function in python to find the addition of two numbers is executed successfully.


4. Looping(Patterns)-Pascal's Triangle Generator
# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
import math
a=int(input())
for i in range(a):
     print(""*(a-i),end="")
     for j in range(i+1):
         v=math.comb(i,j)
         print(v,end="")
     print()

## Sample Output
<img width="1919" height="790" alt="m2 o4" src="https://github.com/user-attachments/assets/3fca5b38-3e95-4ab2-beb3-fc2f4754a7c7" />


## Result
Thus Pascal's Triangle Generator in Python is executed successfully.


5. Loops-Palindrome Number check
## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
n=int(input())
t=n
rev=0
while t>0:
    rev=(rev*10)+(t%10)
    t=t//10
if rev==n:
    print(n,"is a palindrome")
else:
    print(n, 'is not a palindrome')
## Output
<img width="1919" height="792" alt="m2 o5" src="https://github.com/user-attachments/assets/8679d2a7-f210-49b8-bad9-b47e855b8d2c" />

## Result
Thus the palindrome check code is executed is successfully.
