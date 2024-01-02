# Word-count

### Name: Divya R V
### Register Number: 23014030
### Department: CSE(CS)

## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file with .txt file extension
### Step 2: 
Add some text in that file
### Step 3: 
Create a python file
### Step 4:  
Write the code to count the number of words in that file
### Step 5: 
Run the program
### Step 6: 
Display the output
## PROGRAM:
### Name:Divya R V
### Register Number: 23014030
```
num=0
with open("PYTHON.txt","r") as f1:
 for i in f1:
        word=i.split()
        num=num+len(word)
print("The number of words are in the file is:",num)
```
### OUTPUT:
![Screenshot 2024-01-02 191444](https://github.com/rdivyav/Word-count/assets/148604723/d52651e6-e0c1-4a66-a0ee-1f08f5e88173)

## RESULT:
Thus the program is written to find the word count from a text.
