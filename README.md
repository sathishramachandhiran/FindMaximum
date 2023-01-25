# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: SATHISH R
RegisterNumber: 22009045
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SATHISH R
RegisterNumber: 22009045
'''
def max_marks(marks):
    
    max=marks[0]
    for i in marks:
        if i>max:
            max=i
    return max
    
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## PROGRAM 1
![P1](https://user-images.githubusercontent.com/120574768/214622344-8c3550d6-2a84-4cc6-906d-487145c071df.png)

## PROGRAM 2

![P2](https://user-images.githubusercontent.com/120574768/214622367-7b28ca94-880e-488a-a803-3ca92c27fbe0.png)

## PROGRAM 3

![P3](https://user-images.githubusercontent.com/120574768/214622407-9d01f66a-da79-4c40-b189-18f8854fb2eb.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
