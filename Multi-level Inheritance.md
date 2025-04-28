# Exp.No:5d
## Multi-level Inheritance

### AIM  
To write a Python program to get the name, age, and ID of a person and display them using multilevel inheritance.

### ALGORITHM

1. Define `Parent` class with an `__init__` method to initialize `name` and a `getName()` method to return it.
2. Define `Child` class that inherits from `Parent`, initializes `name` via `Parent`, and adds age with a `getAge()` method.
3. Define `Grandchild` class that inherits from `Child`, initializes `name` and `age` via `Child`, adds `id` with a `getid()` method.
4. Take user input for `name` (string).
5. Take user input for `age` (integer).
6. Take user input for `id` (integer).
7. Create an object `gc` of `Grandchild` using the inputs.
8. Print the `name`, `age`, and `id` of the grandchild using their respective getter methods.
9. Terminate the program.

### PROGRAM

```
class Parent:
   def __init__(self,name):
     self.name = name
   def getName(self):
     return self.name
class Child(Parent):
   def __init__(self,name,age):
     Parent.__init__(self,name)
     self.age = age
   def getAge(self):
     return self.age
class Grandchild(Child):
   def __init__(self,name,age,id):
     Child.__init__(self,name,age)
     self.id=id
   def getid(self):
     return self.id
name=input()
age=int(input())
id=int(input())
gc = Grandchild(name,age,id)
print(gc.getName(), gc.getAge(), gc.getid())
```

### OUTPUT
![image](https://github.com/user-attachments/assets/9029c7e8-64a4-4540-9405-86e1355f1441)

### RESULT
Thus a Python program to get the name, age, and ID of a person using multilevel inheritance is successfully implemented.
