# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from which we need to copy the text.
### Step 2: 
Using keyword 'with' to open the required file.
 
### Step 3: 
Again using the 'with' keyword to open the empty file.
### Step 4:  
The empty file is open by using 'w' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
write() is used to write the lines of main file to the empty file or to the directed file.
## PROGRAM:
```
#Program to copy the file.
#Developed by: Vishal S
#Register Number: 212223110063

def fun(filename,newfilename):
   with open(filename) as fp:
      with open(newfilename,'w') as fp1:
         data=fp.read()
         fp1.write(data)
filename=input("Enter the file to read the content:")
newfilename=input("Enter the file to store copied content:")
fun(filename,newfilename)
```
### OUTPUT:
![Output](</Screenshot 2024-01-02 151321.png>)
![Output](</Screenshot 2024-01-02 145440.png>)
![Output](</Screenshot 2024-01-02 145448.png>)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
