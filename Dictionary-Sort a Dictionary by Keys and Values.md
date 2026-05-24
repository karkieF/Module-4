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
dictionary = {
    'd': 'dog',
    'b': 'ball',
    'a': 'apple',
    'c': 'cat'
}

sorted_keys = dict(sorted(dictionary.items()))

sorted_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original Dictionary:", dictionary)
print("Dictionary sorted by keys:", sorted_keys)
print("Dictionary sorted by values:", sorted_values)
```

## Sample Output
```
Original Dictionary: {'d': 'dog', 'b': 'ball', 'a': 'apple', 'c': 'cat'}

Dictionary sorted by keys: {'a': 'apple', 'b': 'ball', 'c': 'cat', 'd': 'dog'}

Dictionary sorted by values: {'a': 'apple', 'b': 'ball', 'c': 'cat', 'd': 'dog'}
```
## Result
Thus, the Python program to sort a dictionary by keys and values was executed successfully.

