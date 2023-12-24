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

### OUTPUT:
![Screenshot 2023-12-24 182010](https://github.com/Santhosh-0031/Word-count/assets/145551108/d9daa8fd-1036-489b-a627-736c56c1e0c8)

i)TEXT FILE
![Screenshot 2023-12-24 182205](https://github.com/Santhosh-0031/Word-count/assets/145551108/d0a99f39-7358-4315-80ff-13dd086bdc36)

## RESULT:
Thus the program is written to find the word count from a text.
