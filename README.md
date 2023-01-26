# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a jupyter notebook and open a new text file.

### Step 2: 
Write a sentence and save it with .txt extension.
 
### Step 3: 
Now,create a new python worksheet in jupyter.

### Step 4: 
Get a text file name from user and open it.

### Step 5: 
Enter a code to split a words and count it.

### Step 6: 
Finally run a code to find the number of words in text file.

## PROGRAM:
```
Developed by: Aakashraj M
Register number: 22008579

fname=input('Enter file name:')
nwords=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        nwords+=len(words)
print("Number of words:",nwords)
```
## OUTPUT:
![word count](https://user-images.githubusercontent.com/121117266/214805958-4f012833-cda5-4a8f-a72f-478e2d5901af.jpeg)




## RESULT:
Thus the program is written to find the word count from a text.
