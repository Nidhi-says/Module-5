# Exp.No:5a
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
class Person:
    def __init__(self,name,userid):
        self.name=name
        self.userid=userid
        print(self.userid)
if __name__ == "__main__":
    name=input()
    userid=input()
    obj = Person(name,userid)
```

### OUTPUT
![Screenshot 2025-04-28 133331](https://github.com/user-attachments/assets/fbad8f6f-62b9-4794-a1f5-90760e6bbb57)

### RESULT
Thus a Python code to create a class for a person with a parameterized constructor is implemented successfully.
