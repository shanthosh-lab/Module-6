# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Rectangle:

def init(self, length, width):

self.__length = length  

self.__width = width
r = Rectangle(5, 3)

print(r._Rectangle__length)

print(r._Rectangle__width)

## Output
<img width="206" height="96" alt="488730171-f92af476-5145-43a4-a10a-ccc2dbe479e6" src="https://github.com/user-attachments/assets/1dfcc19b-9ea1-40d2-a0a1-dd9d7c05e21a" />



## Result
Thus the python program excuted successfully.
