# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
~~~
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

f = lambda a, b : a + b

result = f(num1, num2)
print("The sum is:", result)
~~~
## Output
Enter first number: 12
Enter second number: 8
The sum is: 20
## Result
The program successfully demonstrates the use of an anonymous (lambda) function in Python.

The lambda function f is defined with two arguments (a, b) and a single expression (a + b).

Unlike standard functions, lambdas do not require a return statement; the expression result is returned automatically.

This approach produces a concise and readable way to perform basic arithmetic.
