# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program:

<img width="1689" height="704" alt="image" src="https://github.com/user-attachments/assets/3a990f0f-6bdd-4ec4-b417-1b41602a73cd" />



## Output:

<img width="1689" height="704" alt="image" src="https://github.com/user-attachments/assets/03482be6-b449-4ead-b03f-f65d4f4704ff" />


## Result:

The program successfully handled the IndexError exception by displaying an error message when the user tried to access an index outside the range of the list.
