# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
a=[1,2,-8]
print (sum(a))
```
## Output

<img width="360" height="133" alt="Screenshot 2025-10-20 110612" src="https://github.com/user-attachments/assets/576a6f89-a256-4882-87d0-eecd8e03021f" />


## Result
Thus,the python program has been executed successfully



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
```
def remove (d):
    
    ty=d[:g]+d[g+1:]
    return ty
g=int(input ())
sd=remove ("Intelligence ")
print (sd)
```
## Output


<img width="726" height="230" alt="Screenshot 2025-10-20 111612" src="https://github.com/user-attachments/assets/78ce159b-a845-4ddf-8956-7492dfdedfb1" />



## Result

Thus,the python program has been executed successfully



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
```
def palindrome(a):
    reversep=""
    for i in a:
        reversep=i+reversep
 
    
    # Add your code here
    if a==reversep:
        print("The entered string is palindrome")
    else:
        print("The entered string is not palindrome")
        
        
string =input()
palindrome(string)
```


## Output


<img width="1008" height="227" alt="Screenshot 2025-10-20 112046" src="https://github.com/user-attachments/assets/d18e731f-e725-4ee6-af22-6894f2e29771" />


## Result
Thus,the python program has been executed successfully



# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

```
tu=eval(input())
print("n" not in tu) 
print('8' in tu)
```
## Output

<img width="883" height="235" alt="Screenshot 2025-10-20 112327" src="https://github.com/user-attachments/assets/e3b78487-831f-4c2a-bcda-7d9098545a1c" />



## Result
Thus,the python program has been executed successfully



