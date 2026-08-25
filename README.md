# Python-Data-Structures---Strings-Tuples
This repository contains Python programs demonstrating string operations (slicing, indexing, reversing) and tuple operations. Includes assignment solutions, examples, and explanations for learning basic Python data structures.

## Overview

This assignment covers essential operations in Python’s sequence data structures:

• Building and combining strings  
• Extracting characters and words using slicing  
• Applying common string methods  
• Creating and manipulating tuples  
• Accessing tuple elements using indexing and slicing  

---


## String Concepts Covered

• String Concatenation  
• Positive & Negative Indexing  
• Slicing (start, end, step)  
• Reversing strings using slicing  
• Extracting specific words  
• Built‑in methods:  
  - `upper()`  
  - `lower()`  
  - `capitalize()`  
  - `count()`  
  - `replace()`  

## String Concatenation
Write a Python program that takes two strings, i.e., string 1 "Hello" and string 2 “get
name” as input from the user, and concatenates them together. Display the
concatenated string as the output.

### Explanation:  
Concatenation means joining two or more strings together. In Python, this is done using the + operator.
```
string1='Hello '
print(string1)
Hello

string2=input('Enter Your Name :')
print(string1 + string2 )

Enter Your Name : Zara
Hello Zara

string3='Welcome to Python programming'
print(string3)

Welcome to Python programming

print(string1+string2+ ',' +string3)
Hello Zara,Welcome to Python programming
```

## String Slicing and Indexing
Write a Python program using the above concatenated string as input and perform
the following tasks:
a. Print the first character of the string.
b. Print the last character of the string.
c. Print the first 5 characters of the string.
d. Print the last 11 characters of the string.
e. Print the string in reverse.
f. Use slicing and print the word “Python” from the existing string.

### Explanation:  
Slicing allows you to extract parts of a string using index positions. Indexing starts at 0 for the first character. Negative indexing starts from the end.
Example
```
# Print the first character of the string.
print(full_string[0])
H
```
## String Methods
a. Convert the sentence to uppercase.
b. Convert the sentence to lowercase.
c. Use Capitalize and return the sentence to the original input form.
d. Count the total number of occurrences of character ‘t’ in the string.
e. Replace all occurrences of “Python” with “Data Analytics” in the input string
strM = “Python beginner tutorial.”

### Explanation:  
Python provides built‑in methods to manipulate strings.
Example
 ```
strM = "Python beginner tutorial"

print(strM.upper())
UPPERCASE → PYTHON BEGINNER TUTORIAL

#Print the string in reverse.
print(full_string[::-1])

gnimmargorp nohtyP ot emocleW ,araZ olleH

```
##Tuples – Creation, Modification, and Access
###Explanation:  
Tuples are immutable sequences in Python. They can store multiple values and allow indexing and slicing.

## 🔢 Tuple Concepts Covered
Create the 1st tuple with values -> (10, 20, 30) and the 2nd tuple with values -> (40, 50, 60):

• Creating tuples  
• Concatenating two tuples  
• Repeating tuple elements  
• Accessing elements by index  
• Slicing to retrieve ranges  
• Understanding tuple immutability  

Example
```
tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)

t_combine = tuple1 + tuple2
print(t_combine)
(10, 20, 30, 40, 50, 60)
```

Python Data Structures - Strings & Tuples.ipynb

👩💻 Author
SharuLatha B
Module 4 – Python Basics
Data Structures: Strings & Tuples
