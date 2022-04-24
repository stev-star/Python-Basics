# Python-Basics
This repository contains an Python Article

# Introduction To Python Programming

Python is a high-level,geneal-purpose,interpreted programming language which was created by Guido Van Rossum
and released in 1991.

It is dynamically-typed and garbage-collected and it supports multiple programming paradigms which include procedural,
object-oriented and fuctional programming.

## Why learn Python?

- it is beginner friendly-Python is a great language for the beginner-level programmers and supports the development
 of a wide range of applications.
- python is interpreted-Python is processed at runtime by the interpreter.
- python is object-oriented - Python supports Object-Oriented technique of programming that encapsulates code within objects.
- python is interactive - You can actually sit at a Python prompt and interact with the interpreter directly to write your programs.

## Characteristics of Python

- It can be easily integrated with other programming languages such as C,C++,Java e.t.c.
- It provides high-level-Python is a high-level programming language because programmers don’t need to 
  remember the system architecture, nor do they have to manage the memory.
- Object-Oriented - it focuses design around data and objects, rather than functions and logic.
- extensive standard library -  programmers don’t have to write their code for every single thing unlike
  other programming languages.
- Free and Open-Source - it is completely free to use, even for commercial purposes.

## Applications of Python

- Web Development
- Machine Learning and Artificial intelligence
- Data Science
- Audio and Visual Application
- Software Dvelopment
- Desktop GUI
- Web Scraping Application

## Python Hello World

### Here's how to create a python program that displays "Hello World!"
```python
print("Hello World!")
```

The print() is a built-in function that displays a message on the screen

## Python Identation

Indentation refers to the spaces at the beginning of a code line.

Where in other programming languages the indentation in code is for readability only, the indentation in Python
is very important.

Python uses indentation to indicate a block of code.

 ```python
 for i in range(5):
   print(i)
 ```
    
    
## Comments

Comments start with a #, and Python will render the rest of the line as a comment

#This is a programm to display "Hello World!"
```python
print("Hello World!")
```

## Variables

A Python variable is a reserved memory location to store values. In other words, a variable in a python program 
gives data to the computer for processing.

```python
num=100 
print(num) # 100
place=’Nyahururu’ 
print(place) # Nyahururu
```

## Python Operators

### Arithmetic Operators: 
+, -, /, *, % ,//, **

### Comparison operators: 
>, <, ==, !=, <=, >=
>
### Logical operators:
and, or, not

### Bitwise operators:
<<, |, &, ~, ^, >>

### Assignment Operator:
=, +=, -=, /=, *=

### Identity operators:
is, is not

### Membership operators:
in, not in

## Data types in Python


- ### Numbers
Python includes three numeric types to represent numbers: integers, float, and complex number.
    
 ```python
 amount=1000 # integer
 print(f"Amount provided is ksh{amount}") # Amount provided is ksh1000
 quantity=12.5 # float
 print(f"The required quantity is {quantity}L") # The required quantity is 12.5L
 value= 1+5j # complex
 print(f"The solution is {value}") # The solution is (1+5j)
  ```

- ### Strings
Strings are sequences of character data. The string type in Python is called str.
String literals may be delimited using either single or double quotes.
```python
 greeting =("Hello There")
 print(greeting) # Hello There
    
 name1="py"
 name2="thon"
 print(name1 + name2) # python
    
 person=("Kim")
 print(f"Hello {person}")
 ```
  
  - ### Boolean
Python boolean type is one of the built-in data types provided by Python, which represents one of the two values i.e. True or False.

```python
print(10 > 9) # True
print(6 ==3) # False
print(15 < 11) # False
```
    
- ### List
  Lists are a built-in data type in Python, and one of the most powerful data structures.
  They act as containers and store multiple, typically related, items under the same variable name.
  Items are placed and enclosed inside square brackets, []. Each item inside the square brackets is separated by a comma, ,.
    
```python
colors=['green','red','blue']
colors.append('yellow')
print(colors) # ['green', 'red', 'blue', 'yellow']
colors.insert(4,'black')
print(colors) # ['green', 'red', 'blue', 'yellow', 'black']
del colors[1]
print(colors) # ['green', 'blue', 'yellow', 'black']
colors.pop()
print(colors) # ['green', 'blue', 'yellow']
colors.remove('blue')
print(colors) # ['green', 'yellow']
```
- ### Tuple

A Tuple is a collection of Python objects separated by commas. In someways a tuple is similar to a list 
in terms of indexing, nested objects and repetition but a tuple is immutable unlike lists which are mutable.
items are enclosed inside brackets ().

```python
rgb=('red','green','blue')
print(rgb) # ('red', 'green', 'blue')
print(rgb[0]) # red
```
- ### Dictionary

Dictionary in Python is an unordered collection of data values, used to store data values like a map,
which, unlike other Data Types that hold only a single value as an element, Dictionary holds key:value pair.
The first way is by using a set of curly braces, {}, and the second way is by using the built-in dict() function.

```python
person={'name':'john',
'age':21,
'country':'Kenya',
'programming_language':'Python'}
print(person['age']) # 21
print(person['name'] # john

# adding a new key-value
person['Hobby']='Swimming'
# deleting a key-value
del person['country']
```

- ### Set

Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements. 
The order of elements in a set is undefined though it may consist of various elements.
Sets are written with curly brackets {}.

```python
fruits={"apple", "banana", "cherry","mango","pawpaw","pineapple"}
print(fruits)

# adding a fruit
fruits.add('watermelon')
# removing a fruit
fruit.remove('pawpaw')
fruit.discard('cherry')
# removing all elements
fruits.clear() # set()
```



