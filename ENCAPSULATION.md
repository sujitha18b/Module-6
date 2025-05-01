# Exp.No: 6C
## Encapsulation


### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.



### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**



### PROGRAM

class Student: <br />
    def __init__(self,name,age): <br />
        # private member  <br />
        self.name = name  <br />
        self.__age = age  <br />

    
 def get_age(self): <br />
        return self.__age <br />

    
 def set_age(self,age): <br />
        self.__age = age  <br />

stud = Student('Jessa', 14) <br />
print('Name:', stud.name, stud.get_age()) <br />

stud.set_age(16) <br />


print('Name:', stud.name, stud.get_age()) <br />

### OUTPUT

![image](https://github.com/user-attachments/assets/ac174b60-5b20-4597-9090-baa9ef49e82f)

### RESULT
Thus the python program to create a class Student with the private members name and age, and add getter and setter methods has been executed


