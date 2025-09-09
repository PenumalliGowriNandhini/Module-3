## Exp.No:3c
LIST - EVEN NUMBERS LIST
# AIM
To write a Python function that accepts a number N and creates a list containing all even numbers up to N.

# ALGORITHM
1.Begin the program.

2.Accept an integer a from the user.

3.Create an empty list l.

4.Use a for loop to iterate through numbers from 1 to a - 1:
For each number i, check if it is even using i % 2 == 0.

5.If it is even, append i to the list l.

6.Print the final list l containing all the even numbers.

7.Terminate the program.
# PROGRAM
```
# REGNO:-212222060175
# Name:-Penumalli GowriNandini
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
