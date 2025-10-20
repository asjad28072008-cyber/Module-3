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
