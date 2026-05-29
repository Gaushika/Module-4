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
d = {'banana': 3, 'apple': 4, 'pear': 1, 'orange': 2}

sorted_by_keys = dict(sorted(d.items()))
print(sorted_by_keys)

sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))
print(sorted_by_values)
```
## Sample Output
<img width="559" height="159" alt="{066988B0-E16A-4C4D-85F8-ECFE14C2CF8F}" src="https://github.com/user-attachments/assets/c0e26cd3-30cb-437e-9d52-364d800c6924" />

