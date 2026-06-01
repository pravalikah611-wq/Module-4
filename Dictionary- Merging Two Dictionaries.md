## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program:
# Create two dictionaries
dict1 = {'a': 10, 'b': 20}
dict2 = {'c': 30, 'd': 40}

# Method 1: Using dictionary unpacking
merged_dict = {**dict1, **dict2}

# Display result
print("Dictionary 1:", dict1)
print("Dictionary 2:", dict2)
print("Merged Dictionary:", merged_dict)

<img width="1842" height="662" alt="image" src="https://github.com/user-attachments/assets/5f1f65aa-2501-40f7-915d-5bf5ca192a7c" />


## Output:

<img width="1842" height="662" alt="image" src="https://github.com/user-attachments/assets/fdbadd1d-0560-481d-8508-2cff3bac9e08" />


## Result:

The two dictionaries were successfully merged, and their key–value pairs were combined into a single dictionary and displayed as output.
