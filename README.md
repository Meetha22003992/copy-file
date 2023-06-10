# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the first file in read mode.
### Step 2: Again open the second file in append mode, so that we can make changes in it.
### Step 3: Read the line in first file and write the line which was read in the second.
## PROGRAM:
```
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Meetha22003992/copy-file/assets/119401038/55d1a0f4-b689-42ec-a029-9031b0a4b098)

![image](https://github.com/Meetha22003992/copy-file/assets/119401038/b640a1ab-83f0-43a2-b0d0-c0424b9deda6)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
