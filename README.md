# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 
Step 1:

Create a text1.txt with some content in it

Step 2:

Open the text1.txt file in read mode

Step 3:

Create a copy.txt file using write mode

Step 4:

Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Programmed By:DINESH KUMAR R
RegisterNumber: 212222110010

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/DINESH18032004/copy-file/assets/119477784/df807a30-5bcf-4674-a960-b174a11c06d1)
## RESULT:

Thus the program is written to copy the contents from one file to another file.
