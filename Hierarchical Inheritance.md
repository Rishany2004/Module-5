# Exp.No:25  
## Hierarchical Inheritance

### AIM  
To create a Python program that calculates the addition, subtraction, and division using multiple inheritance.
### ALGORITHM

1. Define class c1 with a method add(self, a, b) to return the sum of a and b.
2. Define class c2 with a method sub(self, a, b) to return the difference between a and b.
3. Define class divi that inherits from both c1 and c2, and add a method div(self, a, b) to return the division result of a and b.
4. Take user input for a and b.
5. Instantiate the class divi.
6. Call the add(), sub(), and div() methods to perform the respective operations.
7. Display the results.
8. Terminate the program.

### PROGRAM
```
class c1:  
    def add(self, a, b):  
        return a + b  

class c2:  
    def sub(self, a, b):  
        return a - b  

class divi(c1, c2):
    def div(self, a, b):  
        return float(a / b)  

a = int(input())
b = int(input())
d = divi()  
print(d.add(a, b))  
print(d.sub(a, b))  
print(d.div(a, b))
```
### OUTPUT  

![image](https://github.com/user-attachments/assets/34f5ff13-1bc6-4873-8a4b-286c518476c9)

### RESULT
Thus the Python program to perform addition, subtraction, and division using multiple inheritance has been implemented and executed successfully.
