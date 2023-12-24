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
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:

<img width="624" alt="290153012-e2607a56-d4e8-43ec-8435-b1dc6584168c" src="https://github.com/Naveen1825/Square-root-of-a-number/assets/138969868/0a5c8ea2-5a4a-4818-9f7b-484b9f147c9a">


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
