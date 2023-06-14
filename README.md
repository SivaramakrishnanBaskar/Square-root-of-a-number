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
Program to find the square root for the given number(newton's method) using function.
Developed by: Sivaramakrishnan B
RegisterNumber: 212222110044

def newton_methods(x,x_iters=100):
    a= float(x)
    for i in range(x_iters):
        x=0.5*(x+a/x)
    return x
a=int(input())
print("Square root of the number:",newton_methods(a))
```
## Program Statement: 
![image](https://github.com/SivaramakrishnanBaskar/Square-root-of-a-number/assets/119476322/8bbde879-a091-47d3-b709-cecda7a76228)

## Output:
![image](https://github.com/SivaramakrishnanBaskar/Square-root-of-a-number/assets/119476322/284e8b58-f886-45c6-9ffc-5861bcb0bb04)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
