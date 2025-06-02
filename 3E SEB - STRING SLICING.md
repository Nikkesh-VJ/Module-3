# Exp.No:3(e)	SEB- STRING SLICING
- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
### AIM
To write a python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Take a slice of input_string starting from index 2 up to index 10.

Step 3:	 Reverse the substring.

Step 4:	 slice the reversed string, extracting every second character, starting from the first.

Step 5:	 Print the sliced string in the above step.

Step 6:	 Terminate the program.
### PROGRAM
```
def slice(input_string):
    substring = input_string[2:10:]
    reversed_substring = substring[::-1]
    print(f"The reversed string is '{reversed_substring[::2]}'")
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/1c3e5d33-4525-44e9-93c4-3431af135a04)

### RESULT
Thus the python function that accepts the string. Form a new string by reversing the characters in the given string from 4 th position to 10  th position with alternate characters and print the new string was implemented and executed successfully.
