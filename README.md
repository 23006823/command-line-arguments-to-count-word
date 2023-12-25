# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a new file in visual studio code and type the words in that files
### Step 2: 
 save the file and after opening new folder type the required code to generate the program
### Step 3: 
import sys from the module
### Step 4:  
split the word count using command line arguments
### Step 5: 
print the len(words())
### Step 6: 
end of the program

## PROGRAM:
 ```
#to find word count using command line arguments
#developed by:M GAYATHIRI ROSHINI
#register no:23006823
import sys
if len(sys.argv) == 2:
word_count = len(sys.argv[1].split())
print(f"Number of words: {word_count}")
else:
print("Usage: python word_count.py <text>")
 ```
### OUTPUT:
![image](https://github.com/23006823/command-line-arguments-to-count-word/assets/138971409/9d553a93-3833-40b2-9f18-3b3d818d60ab)
![image](https://github.com/23006823/command-line-arguments-to-count-word/assets/138971409/c8286260-8cc0-4827-9dc9-9fe80085432a)
![image](https://github.com/23006823/command-line-arguments-to-count-word/assets/138971409/203d6505-7e3f-4953-b906-e28b65b24810)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
