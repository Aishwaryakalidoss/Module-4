# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
class calc:
    def setvalues(self,a,b):
        self.a=a
        self.b=b
    def modulo(self):
        return self.a % self.b
    def division(self):
        if self.b!=0:
            result= self.a/self.b
            if result.is_integer():
                return int(result)
            else:
                return result
        else:
            return "Error"
calc_instance=calc()
a=int(input())
b=int(input())
calc_instance.setvalues(a,b)
while True:
    choice=int(input())
    if choice==1:
        print(f"Result:  {calc_instance.modulo()}")
    elif choice==2:
        print(f"Result:  {calc_instance.division()}")
    elif choice==0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")


```

### OUTPUT
<img width="438" height="327" alt="image" src="https://github.com/user-attachments/assets/51dc2938-a60f-424e-8d0b-484621d89316" />

### RESULT
Thus, the Python program to perform modulo and floor division operations using the class SEC has been successfully executed and the output is verified.
