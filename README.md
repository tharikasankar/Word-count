# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: To write a python program for getting the word count from a text file

### Step 2: Open the required file by using the function "with"
 
### Step 3: Then use tha laptop to assign the i value in the file

### Step 4: Using split function to split the words 

### Step 5: Finding the given length of the words by using len() function

### Step 6: Calling the function and Printing the number of words

## PROGRAM:
```
#Developed by: THARIKA S
#Register num: 212222230159
num_words=0
with open('shara.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words += len(word)
print('num of words={}'.format(num_words)) 
```

### OUTPUT:
![image](https://github.com/tharikasankar/Word-count/assets/119475507/11138a0f-cd65-439b-baa6-e9c655bc9811)



## RESULT:
Thus the program is written to find the word count from a text.
