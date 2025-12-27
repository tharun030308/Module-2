# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```

def result(a,b):
        return a%b
try:
    a=int(input())
    b=int(input())    
    
    if b==0:
        print("a is not allowed to divide by b")
    else:
        modulo=result(a,b)
        print("modulo is",modulo)
except value:        
           print("please enter the correct value")

```
## Output
<img width="1023" height="340" alt="image" src="https://github.com/user-attachments/assets/4e07c492-6a0e-4255-9be7-029b624785b0" />

## Result
Thus, the python program was executed successfully
