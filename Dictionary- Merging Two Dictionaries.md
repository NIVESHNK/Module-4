## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program:
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    result = {**dict1, **dict2}
    print(result)

merge()
```


## Output:
<img width="530" height="180" alt="image" src="https://github.com/user-attachments/assets/6b2462d4-df8a-4f23-b256-4194d67bf069" />


## Result:
Thus, the Python program to merge two dictionaries and combine their key-value pairs was executed successfully.
