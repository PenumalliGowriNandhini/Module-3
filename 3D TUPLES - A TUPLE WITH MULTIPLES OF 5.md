# Exp.No:3d
## TUPLES - A TUPLE WITH MULTIPLES OF 5
# AIM
To write a Python program to create a tuple containing all multiples of 5 up to a given number N.

# ALGORITHM
Begin the program.
Accept an integer N from the user.
Use a generator expression inside the tuple() function to create a tuple multiples_of_5 with values starting from 5 up to N - 1, stepping by 5.
Return the tuple multiples_of_5.
Print the resulting tuple.
Terminate the program.
# PROGRAM
l=[]
n=int(input())
for i in range(5,n,5):
    l.append(i)
t=tuple(l)
print(t)
# OUTPUT
<img width="778" height="229" alt="image" src="https://github.com/user-attachments/assets/99a24b2d-e0da-4732-a772-254f3fc6143d" />


# RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number N has been implemented and executed.
