# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 

    1.PC
    2.Anaconda - Python 3.7
    
## ALGORITHM: 

### Step 1:

Get the file name and location from the user.

### Step 2: 

Give a new file name to create a copy of a file content.
 
### Step 3: 

Read the file and close the file.

### Step 4:  

Now write the content in the new file.

### Step 5: 

When done print "File copied successfully".

### Step 6: 

End of the program.

## PROGRAM:
```
'''
Developed by: Tejusve Kabeer.F
RegisterNumber: 22002543
'''
print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()
fileHandle = open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```

### OUTPUT:
![cpyfile](https://user-images.githubusercontent.com/118364993/214795063-41f1428e-ad11-441f-95a9-b373ebc7089d.png)

![file1](https://user-images.githubusercontent.com/118364993/214795143-d1d356e5-a9d2-4e27-85cc-2ce20fa8f66c.png)

![file2](https://user-images.githubusercontent.com/118364993/214795194-7ecdaf24-6195-4ef9-94c1-3538399c9ff3.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
