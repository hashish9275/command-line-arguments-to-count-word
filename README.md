# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a text file in a specific loaction of interest.

## Step 2:
On the same location as the text file, create a python program file.

## Step 3:
In python Program, import sys and open a text file with argument "sys.argv[1]"

## Step 4:
using read() and split(), split the lines in the file into a sequence of words.

## Step 5:
using len() count the number of words in the text file.

## Step 6:
In command prompt, initiate python followed by program name and text file name to get the outpu

## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: K.R.Hashish Vidya Sagar
RegisterNumber:212222230047
'''
import sys
count=0
fp=open(sys.argv[1],'r')
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)
```
### OUTPUT:
![pythonexp 5b](https://github.com/hashish9275/command-line-arguments-to-count-word/assets/118707521/2a791126-421e-4d9e-bb92-c1b7e91f6d43)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
