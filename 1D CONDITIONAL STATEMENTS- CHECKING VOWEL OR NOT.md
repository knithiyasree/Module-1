## Experiment No: 1d – Conditional Statements- Checking even or odd

## AIM  
To Write a Python program to check whether the given  using number is Even number and it is lesser than or equal to 30 or not using nested if..else.
## ALGORITHM 
1. Begin the program.  
2. Read a number from the user.  
3. Check if the number is even.  
   3.1 If yes, check if the number ≤ 30.  
       3.1.1 If yes, display "Even and ≤ 30".  
       3.1.2 Else, display "Even but > 30".  
   3.2 If no, display "Odd".  
4. End the program.  



## PROGRAM
```python
# Reg.No-212223060188
# Name-k.nithiyasree
# Write your code here

n=int(input())
if n%2==0:
    print(f"{n} is an Even number")
    if n<=30:
        print(f"{n} is lesser than or equal to 30")
    else:
        print(f"{n} is greater than 30")
else:
    print(f"{n} is NOT an Even number")
```

## OUTPUT
<img width="792" height="287" alt="image" src="https://github.com/user-attachments/assets/50b7fdf2-a4bc-4d34-95eb-7424ae3ba3e5" />



## RESULT:
Python program to check whether the given  using number is Even number and it is lesser than or equal to 30 or not using nested if..else has been executed successfully.
