```
DONE BY: JAYASHREE J
REGISTER NUMBER: 212225040145
```
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of circle =", area)

r = float(input())

obj = cse()
obj.mech(r)
```
## Output
<img width="927" height="233" alt="image" src="https://github.com/user-attachments/assets/4b6d9dca-b989-4997-8cc3-740fbe626f9f" />

## Result
Hence the task to write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation has been done successfully.

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    result = {**dict1, **dict2}
    print(result)

merge()
```
## Output
<img width="921" height="206" alt="image" src="https://github.com/user-attachments/assets/fbc9a821-5c34-468a-8a53-ea550e04a6c2" />

## Result
Hence the program that merges **two dictionaries** and combines their key-value pairs has been executed successfully.

# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'c': 'cat', 'a': 'apple', 'b': 'ball'}

sort_keys = dict(sorted(d.items()))
sort_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)
print("Sorted by Keys:", sort_keys)
print("Sorted by Values:", sort_values)
```

## Sample Output
<img width="916" height="269" alt="image" src="https://github.com/user-attachments/assets/29b63d6c-c485-483b-95ab-122e95e54eb3" />

## Result
Hence the program write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order
has been executed successfully.

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```
## Output
<img width="921" height="202" alt="image" src="https://github.com/user-attachments/assets/851cc1bc-d8ca-4f68-a471-4594753743cc" />

## Result
Hence the task to write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list has been executed successfully.
