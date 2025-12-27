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
num=int(input())
temp=num
rev=0
while temp>0:
    rev=(10*rev) + (temp%10)
    temp//=10
if rev==num:
    print(f"The number {num} is a palindrome")
else:
    print(f"It is not a palindrome")

```
## Output
<img width="916" height="777" alt="image" src="https://github.com/user-attachments/assets/f38a56fc-7a7d-4e7a-8c46-a4368c9d7da4" />


## Result
The program was run and executed successfully.
