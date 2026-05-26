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
a={5:50,2:"two"}
b={1:10,2:20,3:30}
c=b.copy()
c.update(a)
print(c)
```

## Output

<img width="628" height="173" alt="image" src="https://github.com/user-attachments/assets/86a8b3b6-f544-4853-8398-5d97b48b1c02" />


## Result
Thus the Python program that merges **two dictionaries** and combines their key-value pairs is executed successfully.
