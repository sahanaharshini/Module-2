# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

**AIM**  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---
**ALGORITHM**

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM

Reg.No:212223060236

Name:Sahana Harshini K
```
num=int(input())
s=0
for i in range(1,num):
    if num%i==0:
        s=s+i
    i+=1
if s==num:
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")

```
 OUTPUT
<img width="860" height="265" alt="image" src="https://github.com/user-attachments/assets/6a45bc59-859e-4b9e-91c9-356915fb9fed" />

 RESULT
 Thus a Python program to check if a number is a Perfect number using the concept of functions was executed and implemented successfully.
