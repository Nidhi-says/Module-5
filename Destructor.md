# Exp.No:5b 
## Destructor

### AIM  
To create a Python class `Student` with a destructor.

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `obj` of the `student` class. When the object `obj` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `obj`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

### PROGRAM

```
class Student:
 
    # Initializing
    def __init__(self):
        print('Inside Constructor\nObject initialized\nHello, my name is Emma')
 
    # Deleting (Calling destructor)
    def __del__(self):
        print("Inside destructor\nObject destroyed")
 
obj = Student()
del obj
```

### OUTPUT
![image](https://github.com/user-attachments/assets/1189ddd2-497e-4e85-870e-de361e1c9b23)

### RESULT
Thus a Python class `Student` with a destructor is impemented successfully.
