# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
~~~
a = 16


binary_value = bin(a)

print(binary_value)
~~~
## Output
0b10000
## Result
the program demonstrates the use of the bin() built-in function to convert a decimal integer into its binary equivalent.The output starts with the prefix 0b, which is Python’s way of indicating that the following digits are in binary (base-2).The decimal value 16 is represented as $2^4$, which results in a 1 followed by four 0s in binary ($10000$).
