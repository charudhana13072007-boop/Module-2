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
~~~

def result(a, b):
    
    modulo_val = a % b
    
    
    print(modulo_val)

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

result(num1, num2)
~~~
## Output
Enter first number: 10


Enter second number: 3


1
## Result
The program demonstrates how to encapsulate logic within a user-defined function.

By passing arguments to the result() function, we make the code reusable.

The % operator effectively returns the remainder of the division between the two integers provided.
