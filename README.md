# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
1. Open the first file in read mode.
2. Again open the second file in append mode, so that we can make changes in it.
3. Read the line in first file and write the line which was read in the second.
## PROGRAM:
```
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Meetha22003992/copy-file/assets/119401038/c449035a-74dd-4e1b-9e94-df310b9ce589)

![image](https://github.com/Meetha22003992/copy-file/assets/119401038/84599b9f-28c1-45da-b36c-a58404cfadf0)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
