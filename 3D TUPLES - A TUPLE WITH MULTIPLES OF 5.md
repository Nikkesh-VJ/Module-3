# Exp.No:3(d)	TUPLES- A TUPLE WITH MULTIPLES OF 5
- **Name:** Nikkesh V  
- **Registration Number:** 212222050042
### AIM
To write a python program to create the tuple by the multiples of 5 up to N. Get the N value from the user.
### ALGORITHM

Step 1:	 Begin the program.

Step 2:	 Accept an integer N from the user.

Step 3:	 Define an empty tuple multiples_of_5.

Step 4:	 Loop through the numbers starting from 5, up to N-1 (not including N), with a step size of 5 For each value of i, add i to the tuple multiples_of_5.

Step 5:	 Return the multiples_of_5 tuple.

Step 6:	 print the resultant tuple.

Step 7:	 Terminate the program.
### PROGRAM
```
def create_tuple(N):
    multiples_of_5 = tuple(i for i in range(5, N, 5))
    return multiples_of_5
N = int(input())
result = create_tuple(N)
print(f"{result}")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/a16820ca-d669-4520-b141-c4e0a836c910)


 
### RESULT
Thus the python program for printing a tuple with numbers that are multiples of 5 up to n, was implemented and executed successfully.
