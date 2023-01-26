# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name using command arguments
### Step 2: 
 Get the file name using command arguments
### Step 3: 
use split()
### Step 4:  
Now read the no.of words in file
### Step 5: 
Print number of words present in given file
### Step 6: 
End of the program
## PROGRAM:
```python
# Developed By: shaik sameer basha
# Reference number: 22004926
import sys
count = 0
with open("text.txt",'r') as f:
    for line in f:
        word =line.split()
        count+=len(word)
print("Word count in file: ",count)
```
### OUTPUT:
![5b](https://user-images.githubusercontent.com/118707756/214849729-5fd41dc6-1aa9-4d03-8057-8d7487519ef8.jpg)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
