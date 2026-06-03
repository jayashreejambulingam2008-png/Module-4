# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0

n = int(input("Enter number of lines: "))

for i in range(n):
    line = input()

    if not line.startswith("T"):
        count += 1

print("Number of lines not starting with T:", count)
```
## Output
<img width="924" height="356" alt="image" src="https://github.com/user-attachments/assets/a2f6f1fb-fd45-4f31-9657-ef4cd02f2b15" />

## Result
Hence the task to write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'` has been done successfully. 
