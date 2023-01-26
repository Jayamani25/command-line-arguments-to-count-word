# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open vscode.

### Step 2: 
Type the program.
 
### Step 3: 
save the python file.

### Step 4:
create a text file .

### Step 5: 
Run the program in the vscode, in the terminal type the following commands.

### Step 6: 
End the program.

## PROGRAM:
```
#Developed by: JAYAMANI R
#Reference no: 22008124
import sys
count={}
a=sys.argv[1]
with open(a,'r') as f:
    for line in f:
        for word in line.split():
            if word not in count:
                count[word]=1
            else:
                count[word]+=1
print(count)
f.close()
```
### OUTPUT:
Text File
![Screenshot from 2023-01-26 14-55-56](https://user-images.githubusercontent.com/85949888/214807852-9bfb9eb6-5f80-4e33-b3d8-d885e73af08b.png)

![Screenshot from 2023-01-26 15-28-15](https://user-images.githubusercontent.com/85949888/214807794-05e5d597-1bbd-4dc9-9cac-88915a0feef9.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
