## Exp.No:23  
## SEB-Check Exam Eligibility Using Inheritance
### AIM  
To write a Python program to get the name, attendance, and ID of a student and check their eligibility for the exam using multiple inheritance.

### ALGORITHM

1. Define a base class Person with attributes for name and age.
2. Define a base class Student with an attribute for attendance percentage.
3. Create a derived class Resident inheriting from both Person and Student.
4. Use constructors in each class to initialize the attributes.
5. Create methods to display name and age.
6. Check if attendance is greater than 75 to determine eligibility.
7. Print “Eligible for Exam” or “Not Eligible for Exam” accordingly.

### PROGRAM

```
class Person:  
    def __init__(self, personName, personAge):  
        self.name = personName  
        self.age = personAge  

    def showName(self):
        print(self.name)

    def showAge(self):  
        print(self.age) 
        
class Student:
    def __init__(self, studentpercent):  
        self.studentpercent = studentpercent  
  
    def getpercent(self):  
        return self.studentpercent  
  
class Resident(Person, Student): 
    def __init__(self, name, age, percent):
        Person.__init__(self, name, age)
        Student.__init__(self, percent)

name = input()
age = int(input())
percent = int(input())

resident1 = Resident(name, age, percent)  
resident1.showName()  
resident1.showAge()  

if resident1.getpercent() > 75:
    print("Eligible for Exam")
else:
    print("Not Eligible for Exam")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/520c792a-0ef3-47cc-80bc-a7d320895865)

### RESULT

Thus the Python program to check exam eligibility using multiple inheritance has been executed successfully.


