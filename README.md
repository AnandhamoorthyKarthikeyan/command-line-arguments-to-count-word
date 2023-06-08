# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
import sys

## Step 2:
Assign a variable count =0

## Step 3:
open a file in read mode

## Step 4:
iterate a variable (lines) through the file

## Step 5:
Assign a variable words = lines.split ()

## Step 6:
Now iterate through the variable and increase the count: and print the count vi


## PROGRAM:
```
#Developed By:- ANANDHAMOORTHY.K
#Register number:-212222100004
import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)   
```

### OUTPUT:
![Screenshot 2023-06-08 103437](https://github.com/AnandhamoorthyKarthikeyan/command-line-arguments-to-count-word/assets/119475998/cf02523b-33b2-4438-a3df-ab17793a2fbf)
![Screenshot 2023-06-08 103455](https://github.com/AnandhamoorthyKarthikeyan/command-line-arguments-to-count-word/assets/119475998/c79c0417-5621-4ce2-87cc-d64b58ef7e77)
![Screenshot 2023-06-08 103510](https://github.com/AnandhamoorthyKarthikeyan/command-line-arguments-to-count-word/assets/119475998/c8bdc250-14c4-421f-85ac-39da2627ee75)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
