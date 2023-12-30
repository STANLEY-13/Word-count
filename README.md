# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension
### Step 2: 
Add some text in that file
### Step 3: 
Create a python file
### Step 4:  
Write the code to count the number of words in that file
### Step 5: 
Run the program
### Step 6: 
Display the output
## PROGRAM:
```

#Program to find the number of words in text file
#Developed by: STANLEY S
#RegisterNumber:23014354

num=0
sample=input()
with open(sample,"r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
    print("The number of words are in the files is",num)
```
### OUTPUT:
![image](https://github.com/STANLEY-13/Word-count/assets/148198816/65f53322-8760-47d8-8aa3-2a0d1e613547)
![image](https://github.com/STANLEY-13/Word-count/assets/148198816/94e26542-2624-43ad-833f-0ff5dde0a243)



## RESULT:
Thus the program is written to find the word count from a text.
