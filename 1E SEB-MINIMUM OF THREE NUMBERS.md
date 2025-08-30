# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
To write a Python program to find the minimum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223060188
# Name-K.Nithiyasree
# Write your code here

n1 = float(input())
n2 = float(input())
n3 = float(input())
 
mx = (n1 if (n1 < n2 and n1 < n3) else
     (n2 if (n2 < n1 and n2 < n3) else n3))

print(f"The minimum of {n1}, {n2}, {n3} is {mx}")

```

## OUTPUT
<img width="1052" height="298" alt="image" src="https://github.com/user-attachments/assets/dd59120e-ca8f-47ec-9320-af23948e0823" />

## RESULT
A Python program to find the minimum between three integer numbers using a conditional expression
has been executed successfully.
