Safe Calculator

A beginner-friendly Python project that demonstrates how to handle errors using try and except.

📌 Description

This program:

Takes two numbers as input from the user
Adds them together
Prevents the program from crashing if the user enters invalid input

If the input is not a number, the program prints "invalid".

🧠 Concepts Used

try-except
Error Handling
User Input
Integer Conversion using int()
Addition Operator
print() function

💻 Code

try:
    num1 = int(input("enter your number:"))
    num2 = int(input("enter you number:"))

    print(num1 + num2)

except:
    print("invalid")

▶️ Example Output

enter your number: 5
enter you number: 7
12
enter your number: hello
invalid
