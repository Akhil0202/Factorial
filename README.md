# Factorial
#1st repo
x=int(input("enter a number"))
def fact(n):
    if x==1:
        return 1
    else:
        return x*fact(x-1)
y=fact(x)
print("Factorial is:",y)
