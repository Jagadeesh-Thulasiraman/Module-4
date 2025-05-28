#  Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

##  Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

##  Algorithm

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

## Program

```python


d = eval(input())
print("Keys and Values sorted in alphabetical order by the key")
for k in sorted(d): 
    print((k, d[k]), end=" ")
```

## Sample Output
![image](https://github.com/user-attachments/assets/07dc6ff0-4d4e-42f5-8f4d-2ada74ec9d42)

## Result
Thus,the program is executed successfully.
