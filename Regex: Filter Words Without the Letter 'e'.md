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
```
import re
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']   #'They ate 5 apples and 5 oranges'
pattern=r'^[^e]*$'

w=[i for i in items if re.fullmatch(pattern,i)]
print(w)
```
## Output

<img width="490" height="144" alt="Screenshot 2025-10-20 111045" src="https://github.com/user-attachments/assets/2acc34ab-96bb-4a79-ac20-d4e374d26778" />


## Result
Thus,the python program has been executed successfully
