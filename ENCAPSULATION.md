# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

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

---

### PROGRAM

```
#Reg_no: 212223060288
#Name: Tharun Kumaran G

class Student:
    def __init__(self, name, age):
        self.name = name
        self.__age = age

    def get_age(self):
        return self.__age

    def set_age(self,age):
        self.__age=age
    

stud = Student('Jessa', 14)

print('Name:', stud.name, stud.get_age())

stud.set_age(16)

print('Name:', stud.name, stud.get_age())

```

### OUTPUT

![image](https://github.com/user-attachments/assets/824299a1-7b78-4050-a494-5944a5b357df)

### RESULT

Thus, the python program to create a class `Student` with the private members `name` and `age` has been executed and verified successfully.

