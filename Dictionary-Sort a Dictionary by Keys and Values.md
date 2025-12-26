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
