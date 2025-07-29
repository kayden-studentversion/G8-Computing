# G8-Computing
LEMME SEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEE

# calculator.py

def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Division by zero"
    return x / y

if __name__ == "__main__":
    print("Simple Calculator")
    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))
    op = input("Choose operation (+, -, *, /): ")

    if op == '+':
        print("Result:", add(a, b))
    elif op == '-':
        print("Result:", subtract(a, b))
    elif op == '*':
        print("Result:", multiply(a, b))
    elif op == '/':
        print("Result:", divide(a, b))
    else:
        print("Invalid operation")
