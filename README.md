'''Basic Python Calculator
A simple Python program that performs basic arithmetic operations: Addition, Subtraction, Multiplication, and Division.

How to Use:
Run the script.
Choose an operation (1 for Add, 2 for Subtract, 3 for Multiply, 4 for Divide).
Enter two numbers.
Get the result.
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 1
Enter first number: 10
Enter second number: 5
Result: 15.0
Perfect for beginners to practice Python functions and conditionals!'''
# Python_Basic_Calculator_Project
def add(x,y):
    return x+y
def subtract(x,y):
    return x-y
def multiply(x,y):
    return x*y
def divide(x,y):
    return x/y
    
print('Welcome to basic Calculator')
print('Select Operation')
print('1.Addition')
print('2.Subtraction')
print('3.Multiplication')
print('4.Division')
while True:
    choice= input('Enter Your Choice:')
    if choice in('1','2','3','4'):
        break
    else:
        print('Invalid Input')
    
num1= float(input('Enter First Number:'))
num2= float(input('Enter Second Number:'))

if choice=='1':
    print(f"Result:{add(num1,num2)}")
elif choice=='2':
    print(f"Result:{subtract(num1,num2)}")
elif choice=='3':
    print(f"Result:{multiply(num1,num2)}")
elif choice=='4':
    if num2!=0:
        print(f"Result:{divide(num1,num2)}")
    else:
        print('Error: Division by 0 is not allowed')
    
