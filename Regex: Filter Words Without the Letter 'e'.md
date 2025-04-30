## EX.NO:3(C)	Regex in Python: Filter Words Without the Letter 'e'
## AIM:
To filter all elements that do not contain e. items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
## ALGORITHM:
Step 1: import the module regex and create an empty list

Step 2: iterate the input and use conditional statements with condition as if not re.search(r"e",i) 

Step 3: append the words which satisfies the condition

Step 4: print the appended list.
## PROGRAM:
```
import re l1=[]
items=['goal', 'new', 'user', 'sit', 'eat','dinner'] 
for i in items:
   if not re.search(r"e",i): 
      l1.append(i)
print(l1)
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/72332b9e-de91-4aa6-a9c3-0a3892f44fa3)

## RESULT:
Thus, the program has been successfully executed.
