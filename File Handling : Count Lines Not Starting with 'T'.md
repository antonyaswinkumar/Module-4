# File Handling in Python: Count Lines Not Starting with 'T'

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
