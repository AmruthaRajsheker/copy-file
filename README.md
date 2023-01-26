# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Open the required file from which the text is to be copied 
### Step 2: 
Open the required file using keyword "with"
### Step 3: 
Create a new empty file
### Step 4:  
The empty file is opened with write only command 
### Step 5: 
The function is used to take each file from main file
### Step 6: 
Run the program and the file is copied to new file

## PROGRAM:
```
Program Developed by : AmruthaRajsheker
Regester Number : 22004501

with open ('f1.txt','r') as firstfile:
    with open ('f2.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

## OUTPUT:
![output](/a1.png)
![output](/a2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.