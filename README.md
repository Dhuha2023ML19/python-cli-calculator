# python-cli-calculator

try:
    a=int(input("Enter a 1st number:"))
    b=int(input("Enter a 2nd number:"))
    Operator=input("Enter an operator +,-,*,/,//,%,**:")
    
    if Operator=="+":
        print(a+b)
    elif Operator=="-":
        print(a-b)
    elif Operator=="*":
        print(a*b)
    elif Operator=="/":
        print(a/b)
    elif Operator=="//":
        print(a//b)
    elif Operator=="**":
        print(a**b)
    elif Operator=="%":
        print(a%b)
    else:
        print("Invalid operator entered!")
except ValueError:
    print("Please enter a valid number!")
except ZeroDivisionError:
    print("Make sure you are not dividing by zero!")
