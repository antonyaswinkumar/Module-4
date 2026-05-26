## Python Programming Module 4
## Name: Antony Aswin Kumar L
## Register Number: 212225040024


## Ex:1  Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program:

```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input("Enter the Radius: "))

obj = cse()
obj.mech(r)
```

## Output

<img width="543" height="346" alt="image" src="https://github.com/user-attachments/assets/250c8da6-0d64-4664-ae13-dc223187b72f" />


## Result
Thus the Python program that calculates the **area of a circle** based on the radius provided by the user is executed successfully.


## Ex:2  Dictionary Operations in Python: Merging Two Dictionaries

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



## Ex:3  Dictionary-Python Program to Sort a Dictionary by Keys and Values

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

## 🧪Program:

```
data={2:56,1:2,5:12,4:24,6:18,3:323}
sort=dict(sorted(data.items()))
print("Keys and Values sorted in alphabetical order by the key")
for key, value in sort.items():
    print(f"({key}, {value}) ",end="")
```


## Output

<img width="686" height="192" alt="image" src="https://github.com/user-attachments/assets/d4b2570d-1d2c-4edc-825e-a7c459f9b0df" />


## Result
Thus the Python program demonstrates how to sort a dictionary Alphabetically by keys and  Alphabetically by values is executed successfully.



## Ex:4  Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program:

```
l=[5,10,30,200]

try:
    print(l[5])
except:
    print("You're out of range.")
```

## Output

<img width="546" height="193" alt="image" src="https://github.com/user-attachments/assets/87a29ccf-2849-4c83-b2c4-4466ae77bfb2" />


## Result:
Thus the Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is executed successfully.



## Ex:5  File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program:

```
file=open("story.txt","r") 
count=0 
for lines in file: 
    if lines [0] not in 'T': 
        count+=1 
print(count)
```

## Output:

GIVEN TEXT FILE:
<img width="841" height="299" alt="image" src="https://github.com/user-attachments/assets/b111157b-52fb-47d5-8eff-34a1cc79bf69" />

<img width="365" height="188" alt="image" src="https://github.com/user-attachments/assets/ee5a1cc0-7ff5-40d4-b23b-31c0975b2594" />


## Result:
Thus the Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.
