## Dictionary Operations in Python: Merging Two Dictionaries

##  Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

##  Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

##  Program

```python


dict1 = eval(input())
dict2 = eval(input())
merged_dict = {**dict1, **dict2}
print(merged_dict)

```

## Output
![image](https://github.com/user-attachments/assets/0ec18a53-a379-4fe3-8c97-a33ceb2e52b1)

## Result
Thus,the program is executed successfully.
