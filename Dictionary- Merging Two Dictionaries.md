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


<img width="1579" height="656" alt="image" src="https://github.com/user-attachments/assets/e4e55513-331a-42c1-814d-fdf8b07bc7df" />


## Output:


<img width="1579" height="656" alt="image" src="https://github.com/user-attachments/assets/e4c2ab8e-7d9d-4d09-bde9-fd7a6453f6cc" />


## Result:

The two dictionaries were successfully merged, and their key–value pairs were combined into a single dictionary and displayed as output.
