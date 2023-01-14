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
```py
def square_root(x,iteration=100):
    a=float(x)
    for i in range(iteration):
        x = 0.5*(x+a/x)
    return x
z=int(input())
print("Square root of the number:",square_root(z))
```

## Output:
![gcd of two number](/Screenshot%202023-01-14%20194730.png)
![output](/Screenshot%202023-01-14%20194801.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
