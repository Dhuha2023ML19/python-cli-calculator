# python-cli-calculator

a=int(input("Enter a 1st number:"))
Operator=input("Enter an operator +,-,*,/,//,%,**:")
b=int(input("Enter a 2nd number:"))

#put if else condition
if Operator=="+":
    print(a+b)
elif Operator=="-":
    print(a-b)
elif Operator=="*":
    print(a*b)
elif Operator=="/":
    print(a/b)
elif Operator=="//":
    print(a/b)
elif Operator=="**":
    print(a**b)
