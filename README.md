# The-Beginning
var1=int(input("Enter the first number:"))
op=   (input("Enter the operation:"))
var2=int(input("Enter the second number:"))
if op=="+":
    print(var1+var2)
elif op=="-":
    print(var1-var2)
elif op=="*":
    print(var1*var2)
elif op=="/":
    print(var1/var2)
elif op=="**":
    print(var1**var2)
elif op=="%":
    print(var1%var2)
else:
    print("Syntax Error")
