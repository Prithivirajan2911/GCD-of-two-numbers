# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use While() loop to find the GCD of the two numbers.

## Program:
```
\*
Program to find the gcd of two number using function.
Developed by: PRITHIVIRAJAN V
RegisterNumber: 23003859
\*
def gcd():
    a=int(input())
    b=int(input())
    while(b!=0):
        a,b=b,a%b
    print("GCD of two numbers is:",a)
```
## Output:
![output](https://github.com/Prithivirajan2911/GCD-of-two-numbers/assets/147020085/7fb7fe03-809f-4b9a-95ae-485e56168b1b)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
