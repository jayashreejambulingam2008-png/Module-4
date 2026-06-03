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
