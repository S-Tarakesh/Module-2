# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
print("Starting Program!")
n=int(input("Enter the number of rows: "))

for i in range(1,n+1):
    for j in range(n-i+1):
        print(' ',end='')
    C=1
    for j in range(1,i+1):
        print(' ',C,sep="",end="")
        C=C*(i-j)//j
    print()
print("End of Program")
```
## Sample Output
<img width="917" height="778" alt="image" src="https://github.com/user-attachments/assets/70a3af8b-1e09-4ce4-817d-e71934bd6bed" />

## Result
The program was run and executed succesfully.
