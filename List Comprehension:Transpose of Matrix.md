# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
n=int(input())
 scl=int(input())
 l=[]
 for i in range(n):
 x=float(input())
 l.append(x)
 sq_l=[item*scl for item in l]
 print(l)
 print(sq_l)

## OUTPUT:
<img width="715" height="335" alt="image" src="https://github.com/user-attachments/assets/96a142e0-066d-43ed-998d-aae4dea3ce01" />

## RESULT:
Thus the program was executed successfully

