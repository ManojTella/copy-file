# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start.

### Step 2: 
Open the first file in read mode by an appropriate method.
 
### Step 3: 
Open the Second file in write mode by an appropriate method.

### Step 4:  
Loop until a variable 'i' in the first file.so Variable i propagates all over the content.

### Step 5: 
Write the value of 'i'in the second file by following method.SecondfileName.write(i)

### Step 6: 
Stop

## PROGRAM:
```
#Develpoed By:Manoj Guna Sundar Tella
#Reference No:21003796
with open('first.txt','r') as firstfile, open('second.txt','W') as secondfile:
    for line in firstfile:
             secondfile.write(line)
```
### OUTPUT:
![Github logo](copy.png)
![Github logo](copy1.png)
![Github logo](copy2.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
