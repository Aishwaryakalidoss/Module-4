# Exp.No:18  
## FILES - FREQUENCY OF CHARACTERS IN A FILE

---

### AIM  
To write a Python program that reads a file and counts the frequency of each character in it.

---

### ALGORITHM

1. Begin the program.  
2. Define the function `create_file()` that accepts two arguments:  
   - `file_path`: The path to the file.  
   - `content`: The string content to be written into the file.  
3. Open the file specified by `file_path` in write mode (`'w'`), and write the provided `content` into the file.  
4. Close the file (this is automatically done when exiting the `with` block).  
5. Define the function `character_frequency()` that accepts one argument:  
   - `file_path`: The path to the file whose character frequency is to be calculated.  
6. Open the file specified by `file_path` in read mode (`'r'`), and read its content into the variable `content`.  
7. Initialize an empty dictionary (`d1`) to store the frequency of each character using `defaultdict(int)`.  
8. Loop through each character in the `content`:  
   - For each character `ch`, increment its corresponding frequency in the dictionary `d1`.  
9. Return the dictionary `d1`, which contains the frequency of each character in the file.  
10. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
from collections import defaultdict

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def char_frequency(file_path):
    a = defaultdict(int)
    with open(file_path, 'r') as file:
        content = file.read()
        for c in content:
            a[c] += 1
        return a

file_path = 'example.txt'
file_content = input()
create_file(file_path, file_content)
print("Character frequencies:", char_frequency(file_path))
```


### OUTPUT
<img width="1244" height="319" alt="image" src="https://github.com/user-attachments/assets/b7b12410-6e94-4beb-adef-5cdc613e87b3" />


### RESULT
Thus, the Python program to read a file and count the frequency of each character has been successfully executed and the output is verified.
