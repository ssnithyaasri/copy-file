# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Open the required file by using the function "with" in read mode.

### Step 2:
Open the another required file by using the function "with" in append mode to append.

### Step 3:
Use for loop in file1.

### Step 4:
Use write function.

### Step 5:
To write the file 1 content in file 2.

### Step 6:
End the program 

## PROGRAM:
```
with open('sample.txt','r') as file1:
    with open ('san1.txt','a') as file2:
        for line in file1:
            file2.write(line)
```            

### OUTPUT:
![](copyfile1.png)
![](copyfile2.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.