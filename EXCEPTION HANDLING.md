# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
try:
    age = int(input())
    print("Age is:")
    print(age)
    
    if age < 0:
        raise ValueError("Input Correct age.")
    else:
        year_of_birth = 2022 - age
        print("Year of Birth is:")
        print(year_of_birth)
        
except ValueError as e:
    print(e)

```

### OUTPUT
<img width="474" height="252" alt="image" src="https://github.com/user-attachments/assets/47ecf661-fb37-4cd0-aeb9-8207ce54dd70" />

### RESULT
Thus, the Python program to check if the age value is negative and raise an exception using the raise keyword has been successfully executed and the output is verified.
