# python8
Factorial using Global Functions

fact= 1
def factorial(n):
    global fact
    fact= 1
    for i in range(1, n+1):
        fact *=i
    return fact
num= int(input("Enter a number:"))
if num<0:
    print("Cannot derive factorial for negative nuumbers")
else:
    factorial(num)
    print(f" Factorial of {num} is", fact)
