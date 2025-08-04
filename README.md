# task-1-Calculator

This is a simple, interactive command-line calculator bulit with Python.  

Features
Interactive menu-driven CLI interface
Supports four basic operations: Add, Subtract, Multiply, Divide
Handles division by zero gracefully
Infinite loop until user chooses to exit

Demo
Welcome to the Calculator
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit
Enter choice (1-5): 1
Enter first number: 8
Enter second number: 2
Result: 10.0

How to Use

1. When the program starts, you'll see a menu with 5 options.
2. Choose an operation by entering a number from 1 to 5.
3. Enter two numbers when prompted.
4. The result will be printed.
5. The program will loop until you choose "Exit".


Sample Code

def add(a, b):
return a + b

def subtract(a, b):
return a - b

def multiply(a, b):
return a * b

def divide(a, b):
if b == 0:
return "Error! Division by zero."
return a / b

def calculator():
while True:
print("\n--- CLI Calculator ---")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")
print("5. Exit")

choice = input("Enter your choice (1-5): ")  

    if choice == '5':  
        print("Thankyou!")  
        break  

    num1 = float(input("Enter first number: "))  
    num2 = float(input("Enter second number: "))  

    if choice == '1':  
        print("Result:", add(num1, num2))  
    elif choice == '2':  
        print("Result:", subtract(num1, num2))  
    elif choice == '3':  
        print("Result:", multiply(num1, num2))  
    elif choice == '4':  
        print("Result:", divide(num1, num2))  
    else:  
        print("Invalid input")





Technologies Used

Python 3.13.5

VS Code 

Command Line Interface (CLI)


