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
Developed by: DARSHAN S
RegisterNumber: 212222100010
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: DARSHAN S
RegisterNumber: 212222100010
'''
def max_marks(marks):
    max1=max(marks)
    return max1


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: DARSHAN S 
RegisterNumber: 212222100010
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 


## Output:
1.# To find the maximum of marks using the list method sort.
![max of list1 ](https://github.com/Darshans05/FindMaximum/assets/115534676/d993120b-433c-40a8-9612-93d52b60a868)
2.	# To find the maximum marks using the list method max().
	![max of list2](https://github.com/Darshans05/FindMaximum/assets/115534676/ac6891ce-fce0-4396-8a05-87d5b137620b)
3. # To find the maximum marks without using builtin functions.
 ![max of list3](https://github.com/Darshans05/FindMaximum/assets/115534676/0142be9d-774c-4798-b25d-972c1f43d95f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
