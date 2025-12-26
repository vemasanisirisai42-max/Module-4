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
with open('story.txt', 'w') as f:
    f.write("The stars shine brightly tonight.\n")
    f.write("Some lines start with T.\n")
    f.write("Others don't.\n")

count = 0
with open('story.txt', 'r') as file:
    for line in file:
        if not line.startswith('T'):
            count += 1

print("Lines not starting with 'T':", count)

```

## Output
<img width="704" height="678" alt="image" src="https://github.com/user-attachments/assets/4f544d4e-aabf-4321-ab1f-6809c4418aa1" />

## Result
Therefore thr givrn Python program has been executed successfully and the output has been verified.
