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
```
def max_marks(marks):
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max




```
## Sample Input and Output


## Output:
![1](https://github.com/shashinprasad/FindMaximum/assets/129143499/dc580fda-e52b-4c90-882e-b74f5544de0a)
![2](https://github.com/shashinprasad/FindMaximum/assets/129143499/73dfb27a-5f2b-45f6-a152-722aa151cf5d)
![3](https://github.com/shashinprasad/FindMaximum/assets/129143499/5720efe7-729a-403e-a237-2c4f8936a41b)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
