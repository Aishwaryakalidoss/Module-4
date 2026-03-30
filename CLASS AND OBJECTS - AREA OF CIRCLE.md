# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
import math
class pen:
    def stationary(self, r):
        area = math.pi * r ** 2
        print("Area of circle:", round(area, 2))

r = int(input())
p = pen()
p.stationary(r)
```

### OUTPUT

<img width="515" height="162" alt="image" src="https://github.com/user-attachments/assets/bc4b6f3d-e45a-4f73-ae14-e635f884730f" />


### RESULT
Thus, the Python program to find the area of a circle using class name pen and function name stationary has been successfully executed and the output is verified.


