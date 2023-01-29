# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open the file in read mode and handle it in test mode.
### Step 2: 
read text using read() function
### Step 3: 
split the text using space separator.we assume that words in a sentence are separated by a
space character
### Step 4:
the length of the split list should equal the numbers of words in the test file.

### Step 5:
you can refine the count by cleaning the string prior to splitting or validating the words
after splitting.
### Step 6: 
End the program.
## PROGRAM:

```
fname = input("Enter file name: ")
num_words = 0
with open(fname, 'r') as f:
for line in f:
words = line.split()
num_words += len(words)
print("Number of words: ", num_words)

```

### OUTPUT:
![output word](https://user-images.githubusercontent.com/119478098/215328734-c34df6d5-dce6-462b-81b4-99d2d219d587.jpg)




## RESULT:
Thus the program is written to find the word count from a text.
