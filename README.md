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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output



## Output:
![op 1](https://user-images.githubusercontent.com/119394248/215325611-da80fd58-e13d-4a65-a0af-c743af1268a0.png)

![op 2](https://user-images.githubusercontent.com/119394248/215325616-baa4be44-d418-4d22-837d-85bc688204f1.png)

![op 3](https://user-images.githubusercontent.com/119394248/215325623-0ff3bacc-a9d1-40e1-a09b-fabcb836be33.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
