# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
On the same location as the text file, create a python program file. 
### Step 3: 
In python Program,with open() and open a text file of txt file
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words.
### Step 5: 
using len() count the number of words in the text file.
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
# program for getting the word count using command line arguments.
# Developed by:Rohiit.A.S
# Register number:212223100047
fname=input("enter the file name")
num_words=0
with open(fname,'r') as f:
for line in f:
words=line.split()
num_words+=len(words)
print('Number of words: ',num_words)

### OUTPUT:
![exp5b](https://github.com/Rohiit2005/command-line-arguments-to-count-word/assets/138849178/bd389d64-b999-453a-8847-c3661898ee8e)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
