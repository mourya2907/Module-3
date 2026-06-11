# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

~~~
text = input()

rev = text[::-1]

if text == rev:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
~~~

## Output:
<img width="902" height="238" alt="600716446-84f29fcd-5773-47c3-80ec-15c2cc267675" src="https://github.com/user-attachments/assets/13edd970-4b52-411f-a1e2-1fc613f4f7c3" />


## Result:
Thus to write a Python program to check whether the string "malayalam" is a palindrome or not, without using built-in palindrome checking functions is done successfully.
