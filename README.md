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

i) To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large


```

iii) To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```



## Output:
i) To find the maximum of marks using the list method sort.
![Screenshot 2024-03-26 091254](https://github.com/GUGHAN-3001/FindMaximum/assets/150009432/f5ea829a-aae1-466c-a40f-1ae43b7179b6)

ii) To find the maximum marks using the list method max().
![Screenshot 2024-03-26 091254](https://github.com/GUGHAN-3001/FindMaximum/assets/150009432/0490b3ac-a0b8-4e14-ab8f-d199b6c0addb)

iii) To find the maximum marks without using builtin functions.
![Screenshot 2024-03-26 091254](https://github.com/GUGHAN-3001/FindMaximum/assets/150009432/4fb823e2-ba61-4e44-bb68-be4c484981b4)

# Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
