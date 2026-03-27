# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```python
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    print(a)


string = input()
n = int(input())

remove(string, n)
```

## Output

<img width="677" height="178" alt="image" src="https://github.com/user-attachments/assets/18c5a3c0-9b01-4511-9f06-f55f8c3b23a0" />


## Result

Thus , the program has been executed succesfully.
