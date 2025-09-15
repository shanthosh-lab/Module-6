# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
class A:

def init(self, value):

self.value = value
def lt(self, other):

return self.value < other.value
ob1 = A(20)

ob2 = A(3)

if ob2 < ob1:

print("ob2 is less than ob1") else:

print("ob2 is not less than ob1")

## Output
![488719374-b4f44eb6-f2ba-4458-a045-ec104736e489](https://github.com/user-attachments/assets/a1f9f7ef-4a82-4542-893e-20b4ed2d71e5)


## Result
Thus, the program To write a Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class is excuted and verified.
