# Exp.No:3(c)	LIST- EVEN NUMBERS LIST
- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
### AIM
To write a python function that accepts N and to create a list with even numbers up to N.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer a.

Step 3:	 Create an empty list l.

Step 4:	In For Loop, Iterate through the numbers from 1 to a-1.For each number i, check if i is even: If i % 2 == 0, append i to the list l.

Step 5:	 Print the list l which contains all even numbers from 1 to a-1.

Step 6:	 Terminate the program.
### PROGRAM
```def createlist(a):
    l=[]
    for i in range(1,a):
        if (i%2==0):
            l.append(i)
    print(l)
```
### OUTPUT
 ![image](https://github.com/user-attachments/assets/a21369b0-1967-4362-b91f-84bb82becbcd)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.
