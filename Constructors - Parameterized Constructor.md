# Exp.No:21  
## Constructors - Parameterized Constructor

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

### PROGRAM

```
class employee:
    def __init__(self, id, name):
        self.id = id
        self.name = name
    
    def disp(self):
        print(f"Hello my id is : {self.id}")
        print(f"My name is : {self.name}")

id = input()
name = input()
e = employee(id, name)
e.disp()

```
### OUTPUT

![image](https://github.com/user-attachments/assets/3e2b1a51-7322-40ea-bfe7-db4b3744015e)

### RESULT
Thus the Python program to create an employee class with parameterized constructor and display employee details has been implemented and executed successfully.
