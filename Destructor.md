# Exp.No:22  
## Destructor

### AIM  
To create a Python class Vehicle that has a constructor (__init__) and a destructor (__del__). We will create an instance of the class and delete it right after.

### ALGORITHM
1. Begin the program.
2. Define a class vehicle with the constructor __init__(self) to print "Vehicle created." when an object is instantiated.
3. Define a destructor __del__(self) to print "Destructor called, vehicle deleted." when the object is deleted.
4. Create an instance of the vehicle class.
5. The destructor will be automatically called when the object goes out of scope or is explicitly deleted.
6. Terminate the program.

### PROGRAM

```
class vehicle:
    def __init__(self):
        print("Vehicle created.")
    
    def __del__(self):
        print("Destructor called, vehicle deleted.")

v = vehicle()

```
### OUTPUT

![image](https://github.com/user-attachments/assets/2302679c-e138-4057-8ac1-4c1e2edca91a)

### RESULT
Thus the Python program to create a vehicle class with a constructor and destructor has been implemented and executed successfully.
