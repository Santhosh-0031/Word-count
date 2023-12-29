# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open a existing text file

### Step 2: 
read the file and store in the variable
 
### Step 3: 
count=0

### Step 4:  
using for loop split the word

### Step 5: 
using count+=1

### Step 6: 
print the count

## PROGRAM:
```
"""
To write a python program for getting the word count from a text.
Developed by: MIDHUN S 
Reference no: 23003250
"""
with open("myfile.txt","r") as f:
    b=f.read()
    count=0
    for i in b.split():
        count+=1
    print(count)
```

### OUTPUT:
![Screenshot 2023-12-29 185133](https://github.com/Santhosh-0031/Word-count/assets/145551108/ba3dead1-238a-482e-9f14-3076ad41bf10)

i)TEXT FILE
![Screenshot 2023-12-29 185150](https://github.com/Santhosh-0031/Word-count/assets/145551108/900cd6e3-add0-453d-8acb-3bf538be20df)

## RESULT:
Thus the program is written to find the word count from a text.
