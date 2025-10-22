MUTHU GANESH R(25017674)

# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

Add Code Here
```py
# Step 1: Assign the value 16 to a variable
a = 16

# Step 2: Convert the number to binary using bin()
binary_representation = bin(a)

# Step 3: Print the result
print("Binary representation of", a, "is", binary_representation)
```

## Output
<img width="1036" height="161" alt="Screenshot 2025-10-20 143714" src="https://github.com/user-attachments/assets/91a9efa3-114f-4f1d-92e3-ab7bd0332b7c" />

## Result
Successfully wrote a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

Functions in Python: Modulo Calculator
🎯 Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

🧠 Algorithm
Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.
🧾 Program
Add code Here

# Step 1: Define the function
def result(a, b):
    # Step 2: Compute the modulo
    modulo = a % b
    # Step 3: Print the result
    print(f"The result of {a} % {b} is {modulo}")

# Step 4: Get input from the user
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

# Step 5: Call the function
result(num1, num2)
Output
Screenshot 2025-10-20 153905
Result
Successfully wrote a Python program that defines a function which accepts two values and returns their modulo using the % operator.


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
Add code here
```py
# Step 1: Get two integer inputs from the user
a = int(input("Enter the first number: "))  # Example: 12
b = int(input("Enter the second number: ")) # Example: 8

# Step 2: Define a lambda function to add the two numbers
f = lambda x, y: x + y

# Step 3: Call the function and print the result
print(f"The sum of {a} and {b} is {f(a, b)}")
```

## Output
<img width="1014" height="98" alt="Screenshot 2025-10-20 154355" src="https://github.com/user-attachments/assets/cf65a471-8849-4cf4-b688-85c871972429" />

## Result
Successfully wrote a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.
 

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
Add Code Here
```py
import math
rows = int(input("Enter the number of rows: "))

for n in range(rows):
    # Print spaces for triangle shape
    print(" " * (rows - n), end="")

    for k in range(n + 1):
        value = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
        print(value, end=" ")

    print()
```
## Sample Output
<img width="885" height="169" alt="Screenshot 2025-10-20 155229" src="https://github.com/user-attachments/assets/1b29540f-02c3-4c6f-bfdf-e5051ecce914" />

## Result
Successfully wrote a Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

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
Add code Here
```py

num = int(input("Enter a number: "))
temp = num
rev = 0
while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10
if rev == num:
    print(f"{num} is a palindrome.")
else:
    print(f"{num} is not a palindrome.")
```
## Output
<img width="897" height="139" alt="Screenshot 2025-10-20 155846" src="https://github.com/user-attachments/assets/80c626d4-ad9a-45e1-8e66-c9e1c650c9fb" />

## Result
Successfully wrote a Python program that checks whether a given number is a **palindrome** using loops.

