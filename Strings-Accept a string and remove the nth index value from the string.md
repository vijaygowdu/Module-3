## EX.NO:3(A) Strings-Remove Nth Index Character from a String 
## AIM: 
To write a python program to accept a string and remove the nth index value from 
the string. 
## ALGORITHM: 
STEP 1: Define a function named remove that takes two arguments: str (the input 
string) and n (the index to be removed). 

STEP 2: Initialize an empty string a to store the modified string. 

STEP 3: Iterate over each character in the input string using a for loop and the 
range function. 

STEP 4: Check if the current index i is not equal to the specified index n. 

STEP 5: If the indices are not equal, append the character at position i to the string a. 

STEP 6: After iterating over all the characters, return the modified string a. 

STEP 7: Print the modified string.
## PROGRAM:
```
def remove(str): 
  l=len(str) 
  a="" 
  n=int(input()) 
  for i in range(0,l): 
    if i==n: 
        a=a+"" 
    else: 
      a=a+str[i] 
  print(a)
``` 
## OUTPUT:
![image](https://github.com/user-attachments/assets/ad03801e-1792-4f21-be48-71550a59f107)
## RESULT:
Thus the program has been successfully executed
