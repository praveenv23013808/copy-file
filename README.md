# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Open the file f1 in read mode.

### Step 2:Open the file f2 in append mode.
 
### Step 3:Copy the contents using write() with the for loop.

### Step 4:End the program.

## PROGRAM:
```
#Developed By: Praveen v
#Register No: 212222233004
with open('f11.txt','r') as f1:
    with open ('f12.txt','a') as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:
![280465318-c7ea68cd-7200-414e-8953-64e1c85c41fc](https://github.com/praveenv23013808/copy-file/assets/145824728/38fdd817-d41d-41f8-8043-388df00894a7)

![280465356-702f6a3e-eb71-4407-a30b-64354ff0bd74](https://github.com/praveenv23013808/copy-file/assets/145824728/b3318136-afa5-46eb-b1b8-8af4e7f803e1)

![280465407-63382a19-217f-4f85-ab64-aef905de9980](https://github.com/praveenv23013808/copy-file/assets/145824728/1f8db7af-84f4-4152-aca2-5daedcbc8e24)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
