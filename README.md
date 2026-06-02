## EX-1:Conditional Statements in Python: Even or Odd Checker

## Aim:
To write a Python program to check whether the given number is even or odd using if...else statements.

## Algorithm:

1.Get an input from the user.

2.Convert the input to an integer and store it in a variable a.

3.Use the modulo operator % to check if a % 2 == 0.

4.If true, print "EVEN".

5.Else, print "ODD".

6.End the program.

## Program:
```
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")
```

## Output:
<img width="433" height="319" alt="Screenshot 2026-05-29 134252" src="https://github.com/user-attachments/assets/ef250996-de02-4916-b544-f24f3fb5e3f4" />

## Result:
Thus, the Python program to check whether a number is Even or Odd using conditional statements was executed successfully.

## EX-1:Datatypes-Boolean Expression Evaluation in Python

## Aim:
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

## Algorithm:
1.Set variable a to the result of the expression 0 == True.

2.Set variable b to the result of the expression False == False.

3.Set variable c to the result of the expression True + True.

4.Set variable d to the result of the expression False + 9.

5.Print the value of a with the label "a is".

6.Print the value of b with the label "b is".

7.Print the value of c with the label "c:".

8.Print the value of d with the label "d:".

## Program:
```
a = 10
b = 5

print("a > b :", a > b)
print("a < b :", a < b)
print("a == b :", a == b)
print("a != b :", a != b)
print("a >= b :", a >= b)
print("a <= b :", a <= b)
```
## Output:
<img width="315" height="311" alt="Screenshot 2026-05-29 135518" src="https://github.com/user-attachments/assets/b8f90d81-4bd9-4f73-91ab-2a753dc4159a" />

## Result:
Thus, the Python program for Boolean Expression Evaluation using different Boolean data type operations was executed successfully.

## EX-1:Datatypes-Character Literal in Python

## Aim:

To write a Python program that prints the characters 'T' and 'a' using character literals.

##  Algorithm:

1.Print the character 'T'.

2.Print the character 'a'.

## Program:
```
ch = 'A'
print("Character is:", ch)
print("Type of ch:", type(ch))
```
## Output:

<img width="364" height="121" alt="Screenshot 2026-05-29 141450" src="https://github.com/user-attachments/assets/097a8510-46ff-4502-bb9d-567e6a144c64" />

## Result:
Thus, the Python program to demonstrate **Character Literal** was executed successfully, and the character value along with its data type (`str`) was displayed.

## Ex-1:Datatypes-Complex Number Creation in Python

## Aim:
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## Algorithm:

1.Read an integer input from the user and assign it to the variable a (real part).

2.Read another integer input from the user and assign it to the variable b (imaginary part).

3.Create a complex number x using the complex(a, b) function.

4.Print the complex number x.

5.Print the real part of x using x.real. 

6.Print the imaginary part of x using x.imag.

## Program:
```
c1 = 3 + 4j
c2 = complex(5, 2)
print("Complex Number 1:", c1)
print("Complex Number 2:", c2)
print("Type of c1:", type(c1))
```
## Output:

<img width="383" height="190" alt="Screenshot 2026-05-31 092449" src="https://github.com/user-attachments/assets/ff43db7f-5387-4170-a0f7-e6fb25831851" />

## Result:
Thus, the Python program for Complex Number Creation was executed successfully, and the complex number value was created and displayed correctly.

## EX-1:Datatypes-Read and Print a String in Python

## Aim:

To write a Python program to read a string from the user and then print it.

## Algorithm:

1.Assign a variable named men_stepped_on_the_moon.

2.Use input() to read a string from the user and store it in the variable.

3.Print the value stored in the variable.

## Program:
```
s = input("Enter a string: ")
print("Entered string is:", s)

```
## Output:
<img width="349" height="109" alt="Screenshot 2026-05-31 094015" src="https://github.com/user-attachments/assets/8547048f-b720-4c51-b2e2-a0c8f54a6466" />

## Result:
Thus, the Python program to read and print a string was executed successfully, and the entered string was displayed correctly.
