# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
Open the file with sys.argv[1] 
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: THANJIYAPPAN.K
RegisterNumber: 212222240108
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/22009011/command-line-arguments-to-count-word/assets/118343461/04528356-e589-46cc-8478-696d1e0fe189)
![image](https://github.com/22009011/command-line-arguments-to-count-word/assets/118343461/095c2c71-732b-4659-9ac7-917767d37cc7)
![image](https://github.com/22009011/command-line-arguments-to-count-word/assets/118343461/c5b5953c-a747-4f03-80f4-8903eeeac1e3)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
