## Exp.No:3c
LIST - EVEN NUMBERS LIST
# AIM
To write a Python function that accepts a number N and creates a list containing all even numbers up to N.

# ALGORITHM
Begin the program.
Accept an integer a from the user.
Create an empty list l.
Use a for loop to iterate through numbers from 1 to a - 1:
For each number i, check if it is even using i % 2 == 0.
If it is even, append i to the list l.
Print the final list l containing all the even numbers.
Terminate the program.
# PROGRAM
```
def createlist(n):
    l=[]
    for i in range(2,n):
        if i%2==0:
            l.append(i)
    print(l)
```
# OUTPUT
<img width="777" height="201" alt="image" src="https://github.com/user-attachments/assets/077782b0-5eeb-4fef-8a06-7b135bd20979" />


# RESULT
Thus a Python function that accepts a number N and creates a list containing all even numbers up to N has been implemented and executed.
