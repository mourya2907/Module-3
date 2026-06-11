# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

result = [word for word in items if 'e' not in word]
print(result)
~~~
## Output:
<img width="592" height="173" alt="600712646-c644ccba-89f5-40bb-9cf3-ee35928639dd" src="https://github.com/user-attachments/assets/f6c9a8da-828b-4321-baad-d95df8b17107" />


## Result:
Thus to write a Python program that filters out and returns all elements from a list that do not contain the letter 'e', using regular expressions (regex) is done successfully.
