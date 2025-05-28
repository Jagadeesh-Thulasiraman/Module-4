# File Handling in Python: Count Lines Not Starting with 'T'

##  Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

##  Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

##  Program

```python
f = open('story.txt')
c = sum(1 for i in f if i.lstrip() and not i.lstrip().startswith('T'))
print("Lines not starting with 'T':", c)
```

## Output
![image](https://github.com/user-attachments/assets/f64c3037-17af-44f8-88c5-6aa939c45207)

## Result
Thus,the program is executed successfully.
