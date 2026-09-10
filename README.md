# Ex: 1 Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program

```
a=input("Enter the number: ")
a=int(a)
if a%2==0:
   print("EVEN")
else:
   print("ODD")
```

## Output

<img width="494" height="59" alt="image" src="https://github.com/user-attachments/assets/f401f322-fa8e-479b-8dfb-62f8ad68cbb5" />

<img width="493" height="142" alt="image" src="https://github.com/user-attachments/assets/f876d674-d9a2-4baa-bd98-e64f94ffabce" />

## Result

Successfully implemented the Python program to check whether the given number is even or odd using if...else statements.

# Ex 2:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program

```
a=0==True
b=False==False
c=True+True
d=False+9
print("a is:", a)
print("b is:", b)
print("c:",c)
print("d:", d)
```

## Output

<img width="502" height="229" alt="image" src="https://github.com/user-attachments/assets/e1521e88-e4e3-4b7c-80ee-2c8566a0ad48" />

## Result

Successfully implemented the Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

# Ex: 3 Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program

```
print('T')
print('a')
```
## Output

<img width="454" height="209" alt="image" src="https://github.com/user-attachments/assets/a87f0132-1519-4606-94a2-1130eb9a83d3" />

## Result

Successfully implemented the Python program that prints the characters 'T' and 'a' using character literals.

# 🧮 Ex: 4 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program

```
a=int(input())
b=int(input())
x=complex(a,b)
print(x)
print(x.real)
print(x.imag)
```

## Output

<img width="563" height="281" alt="image" src="https://github.com/user-attachments/assets/b6ff0875-6fd3-4af9-9336-5ce3c64e13fa" />

## Result

Successfully developed and implemented a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

# Ex: 5 Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program

```
men_stepped_on_the_moon = input()
print(men_stepped_on_the_moon)
```
## Output

<img width="565" height="215" alt="image" src="https://github.com/user-attachments/assets/d14cca7c-9afd-4b01-a866-2aa03bc5b164" />

## Result

Successfully developed and implemented a Python program to read a string from the user and then print it.
