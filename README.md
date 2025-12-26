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
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())


obj = cse()
obj.mech(r)
```

## Output
<img width="780" height="731" alt="image" src="https://github.com/user-attachments/assets/8260653f-1742-4cb8-a596-aefe5da386d4" />

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
dict1 = {'Ten': 10, 'Twenty': 20, 'Thirty': 30}
dict2 = {'Thirty': 30, 'Fourty': 40, 'Fifty': 50}

def merge(dict1, dict2):
    res = {**dict1, **dict2}
    return res

dict3 = merge(dict1, dict2)
print(dict3)
```

## Output
<img width="992" height="755" alt="image" src="https://github.com/user-attachments/assets/3239a333-8d3d-4376-b60c-3df5f18cab19" />

## Result
thus,the program has been executed successfully.

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
my_dict = {
    'France': 'Paris',
    'Japan': 'Tokyo',
    'India': 'New Delhi',
    'Brazil': 'Brasilia',
    'Canada': 'Ottawa'
}

sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Original dictionary:", my_dict)
print("\nDictionary sorted by keys:", sorted_by_keys)
print("\nDictionary sorted by values:", sorted_by_values)
```

## Sample Output
<img width="1319" height="818" alt="image" src="https://github.com/user-attachments/assets/72ff4b4c-2805-4eb7-97c1-2986aa1ffa85" />

## Result
Therefore the given Python program has been executed successfully and the output has been verified.
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
list1 = [10, 20, 30, 40]

try:
    print("Element at index 5:", list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="822" height="673" alt="image" src="https://github.com/user-attachments/assets/0483f6cf-71ed-4b13-bbb1-1986e9d485fc" />

## Result
Therefore the given Pyhon program has been executed successfully and the output has been verified.
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

## Result
Thus the program executed successfully.
