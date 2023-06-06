# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: BALAMURUGAN B
RegisterNumber: 212222230016
*/
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
         number=0.5*(number +a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![p2 bp](https://github.com/BALA291/Square-root-of-a-number/assets/120717501/b1708a54-2e19-4ba2-b555-96923cbdbbe5)

![p2b o](https://github.com/BALA291/Square-root-of-a-number/assets/120717501/1e986989-d42b-43a2-b243-f423281b1ba6)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
