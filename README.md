# Introduction to Computational Thinking and Computer Programming

## Objective

This course introduces the fundamental building blocks of computational thinking and computer programming using the Python language.

Upon successful completion of this course, students will be able to:
  *  Improve their computational thinking skills
  *  Identify/characterize/define a problem
  *  Design a program to solve the problem
  *  Create executable code
  *  Read most Python code

## Materials

A computer lab which should facilitate the following:

  *  A classroom that can provide each student with access to a computing terminal and Internet access.
  *  The ability to download and install the [ATOM](https://atom.io/) editor on each computing terminal.
  *  A large screen to project the instructor's computing terminal.

## Session 1 : Saturday, November 2, 2019

### Introduction to the course:

  *  Course overview
  *  Course outline/schedule
  *  Student expectations
  *  Resources
  
### Group discussion:

  *  What is programming?
  *  Why should you learn programming?
  *  What is the impact of programming on our world?

### Introduction to computational thinking

  *  Decomposition
  *  Pattern recognition
  *  Abstraction
  *  Algorithm design

### Programming environment setup

  *  Python IDE/Shell
  *  ATOM editor
  *  Python notebooks

### Programming exercise: Hello World

Students will create the most basic Python program possible which will display the words "Hello World" to the screen. This is the de facto first program for all introductory courses in any given programming language.

## Session 2 : Saturday, November 23, 2019

### Introduction to basic data types in Python

  *  None
  *  string
  *  int
  *  float
  *  boolean
  *  list : `[]`
  *  tuple : `()`
  *  dictionary : `{}`

### Typecasting

  *  Usage and pitfalls
  
### Strings

  *  Concatenation
  *  Methods
  *  Slicing
  *  Formatting

### Conditionals and booleans

  *  `if`
  *  `if else`
  *  `if elif`
  *  `if elif else`
  *  `and`
  *  `or`
  *  `not`

### Programming exercise: Truth Table for Booleans

Students will use Python to help fill out a truth table.  A truth table is a breakdown of a logic function by listing all possible values the function can attain.

| P | Q | Statement | Result |
|---|---|-----------|--------|
|`True`||`not P`||
|`False`||`not P`||
|`True`|`True`|`P or Q`||
|`True`|`False`|`P or Q`||
|`False`|`True`|`P or Q`||
|`False`|`False`|`P or Q`||
|`True`|`True`|`P and Q`||
|`True`|`False`|`P and Q`||
|`False`|`True`|`P and Q`||
|`False`|`False`|`P and Q`||
|`True`|`True`|`not (P or Q)`||
|`True`|`False`|`not (P or Q)`||
|`False`|`True`|`not (P or Q)`||
|`False`|`False`|`not (P or Q)`||
|`True`|`True`|`not (P and Q)`||
|`True`|`False`|`not (P and Q)`||
|`False`|`True`|`not (P and Q)`||
|`False`|`False`|`not (P and Q)`||
|`1`|`1`|`P == Q`||
|`1`|`0`|`P == Q`||
|`0`|`1`|`P == Q`||
|`0`|`0`|`P == Q`||
|`1`|`1`|`P != Q`||
|`1`|`0`|`P != Q`||
|`0`|`1`|`P != Q`||
|`0`|`0`|`P != Q`||

## Session 3 : Saturday, February 29, 2020

### Loops

  *  `range()`
  *  `for`
  *  `for else`
  *  `while`

### List comprehension

  *  `[x for x in range()]`
  *  `[x for x in y if <conditional>]`

### Dictionary comprehension

### Set comprehension

### Functions

  *  Definition and use
  *  Arguments
  *  Block structure
  *  Scope and globals
  
### API (application programming interface)

### Programming exercise: Being Pythonic

This programming exercise will focus on list comprehension.  Students will compare the time it takes to perform a task using Python list comprehension to a similar task that does not use Python list comprehension.

The task:

Given a list of values, return a corresponding list with each value squared.

If `values = [1, 2, 3, 4, 5]` then produce a function that returns `[1, 4, 9, 16, 25]`

## Session 4 : Saturday, March 28, 2020

### Exception handling
 
  *  Exception types
      *  `Exception`
      *  `AttributeError`
      *  `IOError`
      *  `ImportError`
      *  `IndexError`
      *  `KeyError`
      *  `KeyboardInterrupt`
      *  `NameError`
      *  `OSError`
      *  `SyntaxError`
      *  `TypeError`
      *  `ValueError`
      *  `ZeroDivisionError`
  *  `try except`
  *  `try except finally`
  *  `try except else`

## Session 5 : Saturday, April 18, 2020

### Working with files

  *  How to read a file
  *  How to read a file piece by piece
  *  How to read a binary file
  *  Writing files in Python
  *  Using the `with` operator
  *  Catching errors

### Programming exercise: Bioinformatics - Calculating GC content

In molecular biology and genetics, GC-content (guanine-cytosine content) is the percentage of nitrogenous bases on a DNA or RNA molecule that are either guanine or cytosine.

GC ratios have been used to help classify bacteria.

Students will be given the task to read in a genome sequence from a file and calculate the GC content of the sequence and try to identify the genome source.

## Session X : Overflow

### Importing

  *  Selective importing using `from <module> import`
  *  Importing everything using `from <module> import *`
  *  Pitfalls of importing everything

### Python libraries

  *  Installing and using Python libraries
      *  [Requests](http://docs.python-requests.org/en/master/)
      *  [Pillow](https://pillow.readthedocs.io/en/latest/)
      *  [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
      *  [matplotlib](https://matplotlib.org/contents.html)
      *  [Scapy](https://scapy.readthedocs.io/en/latest/)
      *  [SymPy](http://docs.sympy.org/latest/index.html)
      *  [wxPython](https://wxpython.org/Phoenix/docs/html/)
      *  [Tweepy](http://docs.tweepy.org/en/v3.5.0/)
      *  [PyTesseract](https://pypi.org/project/pytesseract/)

### Tweepy

  *  Introduction to Tweepy
  *  Hello Tweepy
  *  Learning how to read documentation
    
### Programming exercise: Open lab

In this open lab students will be tasked to explore available Python libraries and select a Python library to learn and use.  Students will be expected to become "experts" for the given Python library and present their findings to the class on how to use the library's API (application programming interface).

The term "expert" is use loosely.  Given that no one is likely to have any background on a given Python library - any iota of knowledge will make the student the classroom "expert".

### Class exercise: Creating a Twitter bot using Tweepy

The class as a whole will go through a group programming session to develop a Twitter bot that will automatically respond to certain tweets.

### Class exercise: Web scraping using Requests and BeautifulSoup

The class as a whole will go through a group programming session to develop a web scraper that will visit a webpage and extract HTML elements for processing.

### Class exercise: OCR (optical character recognition) using PyTesseract

The class as a whole will go through a group programming session to develop a program that will recognize text from an image.

