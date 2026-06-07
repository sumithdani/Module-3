# Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

##  Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```
s = "google"
rev = ""
for i in s:
    rev = i + rev
if s == rev:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

## Output
<img width="527" height="216" alt="image" src="https://github.com/user-attachments/assets/8f9e82a3-c970-4e6f-9ff1-c2f90ab2ba44" />

## Result
Thus, the Python program to check whether the string "google" is a palindrome or not, without using built-in palindrome checking functions, was executed successfully, and the result showed that "google" is not a palindrome.
