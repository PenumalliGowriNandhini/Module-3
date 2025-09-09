# Exp.No:3e
## SEB - STRING SLICING
# AIM
To write a Python function that accepts a string and forms a new string by reversing the characters from the 4th position to the 10th position with alternate characters, and then prints the new string.

# ALGORITHM
Begin the program.
Accept a string as input.
Take a slice of the input string from index 2 to 10 (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).
Reverse the sliced substring.
Extract every second character from the reversed substring using slicing ([::2]).
Print the final processed string.
Terminate the program.
# PROGRAM
```
def slice(a):
    b=a[9:1:-2]
    print(f"The reversed string is '{b}'")
```
# OUTPUT
<img width="755" height="185" alt="image" src="https://github.com/user-attachments/assets/f5016c76-84d3-47be-bb26-5b142444f262" />


# RESULT
Thus a Python function that accepts a string and forms a new string by reversing the characters from the 4th position to the 10th position with alternate characters, and then prints the new string has been implemented and executed.
