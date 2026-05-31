## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
num = int(input("Enter a number: ")) 
temp = num 
rev = 0

while temp > 0: 
    rev = (10 * rev) + temp % 10 
    temp = temp // 10

if rev == num: 
    print("The number is a palindrome.") 
else: 
    print("The number is not a palindrome.")
```
## Output

<img width="1472" height="521" alt="597731815-6eb28ec7-5e94-4c26-b8f8-4da2c222d48f" src="https://github.com/user-attachments/assets/9b5eef15-f763-4b58-9bcf-5f26d51ec51f" />

## Result
Thus To write a Python program that checks whether a given number is a palindrome using loops. Hence the code has been executed successfully.
