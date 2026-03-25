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
Add code here
```
try:
    with open("story.txt", "r") as file:
        count = 0
        for line in file:
            line = line.strip()
            if line and line[0] != 'T':
                count += 1

    print("Number of lines not starting with 'T':", count)

except FileNotFoundError:
    print("File not found! Please check the file name and location.")
```

## Output

<img width="737" height="314" alt="image" src="https://github.com/user-attachments/assets/3277d8d2-d30a-4de8-9ef8-7f995005963b" />


## Result
code executed well as per the question.
