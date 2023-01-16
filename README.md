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
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: E.VARSHA SHARON
RegisterNumber:  22004867
*/
def gcd():
    a=int(input())
    b=int(input())
    if a<b:
        small=a
    else:
        small=b
    for i in range(1,small+1):
        if a%i==0 and b%i==0:
            gcd=i
    print("GCD of two numbers is:",gcd)
```

## Output:
![gcd of two number]![gcd](https://user-images.githubusercontent.com/98278161/212604724-91dad4e8-366e-48dd-81fe-84203b192743.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python program
ming.
