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



## 🧪Program:
# Create a dictionary
my_dict = {'b': 20, 'a': 10, 'd': 40, 'c': 30}

# Sort dictionary by keys (alphabetical order)
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort dictionary by values (alphabetical order)
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
<img width="1651" height="727" alt="image" src="https://github.com/user-attachments/assets/be087955-a2af-4274-9cf1-67564e8e71cc" />


OUTPUT:

<img width="1651" height="727" alt="image" src="https://github.com/user-attachments/assets/e69e9548-57ce-495d-a442-f644b9b62305" />


RESULT:

The dictionary was successfully sorted in alphabetical order based on both keys and values, and the sorted dictionaries were displayed as output.



