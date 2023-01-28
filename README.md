# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
    To write a python program for getting the word count from a text file
### Step 2: 
    open the required file by using the function "with"
### Step 3: 
     then use the laptop to assign the i value in the file
### Step 4:  
     using split function to split the words
### Step 5: 
     finding the given length of the words by using len() function
### Step 6: 
    calling the function and printing the number of words
## PROGRAM:
```
#Developed by: panimalar.p
#RegisterNumber:  22009107
fname = input('Enter file name: ')
num_words = 0
with open(fname,'r') as f:
   for line in f:
       words = line.split()
       num_words += len(words)
print('Number of words: ', num_words)
```

### OUTPUT:

![Screenshot (243)](https://user-images.githubusercontent.com/121490826/215251175-d709afe4-375b-4bc0-9a7a-aa88de9f2953.png)



## RESULT:
Thus the program is written to find the word count from a text.
