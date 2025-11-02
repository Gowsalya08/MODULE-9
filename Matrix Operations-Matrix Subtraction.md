# # ➖ Matrix Operations-Matrix Subtraction in Python

## 🎯 AIM:
To write a Python program that reads two matrices from the user and performs matrix subtraction.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` for rows and columns
3. Get the values of `r` and `c` from the user
4. Define a function `create_matrix(n, m)` to:
   - Prompt user for each matrix element
   - Append each row to form a complete matrix
5. Call the `create_matrix()` function twice to read two matrices `A` and `B`
6. Define a loop to subtract the elements of matrix `B` from matrix `A`
7. Store the result in a new matrix `C`
8. Print the resulting matrix `C`
9. **Stop**

---

## 💻 PROGRAM:
def read_matrix(n):
 matrix=[[0]*n for row in range(n)]
 for i in range(n):
 lines=list(map(int,input().split()))
 for j in range(n):
 matrix[i][j]=lines[j]
 return matrix
 def print_matrix(M):
 print("Matrix:")
 for i in range(len(M)):
 for j in range(len(M[0])):
 if(i>j or i==j):
 print(M[i][j],end=" ")

## OUTPUT:
<img width="618" height="384" alt="image" src="https://github.com/user-attachments/assets/cde3a401-94ec-4d7a-a38d-0f22742e07a8" />

## RESULT:
Thus the program was executed successfully
