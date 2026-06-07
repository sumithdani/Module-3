# Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

##Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
lst = input().split()
result = [word for word in lst if not re.search('e', word)]
print(result)
```
## Output
<img width="435" height="205" alt="image" src="https://github.com/user-attachments/assets/bb4f5459-c2c5-445f-b4e5-cfa62bd6349b" />

## Result
Thus, the Python program to filter out and return all elements from a list that do not contain the letter 'e' using regular expressions (regex) was executed successfully, and the required elements were displayed.
