# Exp.No:3(b)	REGEX-PATTERN MATCHING USING REGEX
- **Name:** Nikkesh V  
- **Registration Number:** 212222050042

### AIM
To write a Python program that matches a string that has an a followed by two to three 'b'.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept a string str1 from the user.

Step 3:	 Define a regular expression pattern as r"[a]+b{2,3}".

Step 4:	 Use the re.match() function to check if the string str1 matches the given pattern. If the string str1 matches the pattern, proceed to step 5. Else If the string str1 does not 
          match the pattern, proceed to step 6.

Step 5:	 Print "Found a match!" if the string matches the pattern.

Step 6:	 Print "Not matched!" if the string does not match the pattern.

Step 7:	 Terminate the program.

### PROGRAM
```import re
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/b473b268-4127-4409-9985-e43d47b02847)

### RESULT
Thus the python program for pattern matching using regular expression was  implemented and executed successfully.
