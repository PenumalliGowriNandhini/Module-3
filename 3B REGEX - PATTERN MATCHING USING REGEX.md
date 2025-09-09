# Exp.No:3b
REGEX - PATTERN MATCHING USING REGEX
# AIM
To write a Python program that matches a string containing an 'a' followed by two to three 'b' characters using regular expressions.

# ALGORITHM
Begin the program.
Accept a string str1 from the user.
Define the regular expression pattern as r"[a]+b{2,3}".
Use the re.match() function to check if the string str1 matches the pattern.
If a match is found, print "Found a match!".
If no match is found, print "Not matched!".
Terminate the program.
# PROGRAM
```
import re
str=input()
x=re.search("bb",str)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
# OUTPUT
<img width="761" height="205" alt="image" src="https://github.com/user-attachments/assets/afb91b9d-667d-4f93-aaa6-2a4ee50d21c9" />


# RESULT
Thus a Python program that matches a string containing an 'a' followed by two to three 'b' characters using regular expressions has been implemented and executed.
