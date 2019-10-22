# EIP STEM Fusion!

## Extra Material

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (**Lunch**)
*  12:20 PM - 1:45 PM (PM Session)
*  1:45 PM (Leave)
*  1:50 PM - 2:00 PM (Departure)

# Review of course material

## Session 1 - Python IDE, ATOM Editor, Windows Command Prompt

*  Hello World!
    *  `print("Hello World!")`
*  Updating PATH environmental variable to include Python
    *  `set PATH=%PATH%;C:\Python##`
*  Executing Python script from the Windows Command Prompt
    *  `cd Documents`
    *  `python hello.py`

## Session 2 - Python Data Types, Typecasting, Strings, Conditionals

*  Data Types
    *  **None** - null
    *  **string** - an array/list of characters
    *  **int** - integer (whole numbers, positive, negative and zero)
    *  **float** - floating point (any rational number)
    *  **boolean** - logical values: `True`/`False`
    *  **list** - `[]`
        *  Methods: `.append()`, `.len()`, `.min()`, `.max()`
    *  **tuples** - `()` an immutable (un-changeable) list
        *  Methods: `.count()`, `.index()`
    *  **dictionary** - `{}` key:value pairs
*  Typecasting
    *  `int(floating_point_number)`
    *  `float(integer)`
    *  `str(number)`
*  Strings
    *  Methods: `.lower()`, `.upper()`, `.swapcase()`, `.strip()`, `.replace()`
    *  Slicing: `string[10:]`, `string[:10]`, `string[:]`, `string[:10]+string[10:]`, `string[-5:]`, `string[:-5]`
*  Conditionals
    *  `if`, `if else`, `if elif`, `if elif else`, `and`, `or`, `not`

## Session 3 - Control Structures

*  Conditional statements

   ```python
   # if-elif-else statement
   shoe="GREEN"
   if (shoe == "RED"):
      print("Shoe is RED")
   elif (shoe == "BLACK"):
      print("Shoe is BLACK")
   else:
      print("Shoe is NEITHER RED NOR BLACK")
   ```

*  For Loop

   ```python
   # for-statement
   alphabet="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
   for letter in alphabet:
      print(letter)

   vowels=["a","e","i","o","u","y"]
   for vowel in vowels:
      print(vowel)

   words=['early','identification','program']
   for w in words:
      print(w, len(w))

   ```

   ```python
   # for-statement over a sequence of numbers
   for i in range(10):
      print(i)

   for i in range(5, 10):
      print(i)

   for i in range(0, 10, 3):
      print(i)

   #for-statement over indices of a sequence
   vowels=["a","e","i","o","u","y"]
   for i in range(len(vowels)):
      print(i, vowels[i])
   ```

*  While Loop (repeated execution when expression is `True`)

   ```python
   # while-statement
   maxValue=50
   x=0
   while (x < maxValue):
      x=x+1
      print(x,"is less than max")
   print(x,"is NOT less than max")
   ```

## Session 4 - Exception Handling

*  Exception types
   *  `ZeroDivisionError`
   *  `IndexError`
   *  `KeyError`
   *  `KeyboardInterrupt`
   *  `AttributeError`
   *  `IOError`
   *  `ImportError`
   *  `NameError`
   *  `OSError`
   *  `SyntaxError`
   *  `TypeError`
   *  `ValueError`

```python
numerator=1
denominator=0
try:
    division_result=numerator/denominator
except ZeroDivisionError:
    print("Denominator is Zero!")
except:
    print("Unable to perform division")
```

## Session 5 - Input/Output and File Handing

*  Opening a file

   ```python
   file_object = open(file_name [, access_mode])
   ```

*  Processing a file
    *  Using `for`

         ```python
         for line in file_object:
             print(line)
         ```

    *  Using `with`

         ```python
         with open('filename.txt') as file_object:
             read_data = file_object.read()
         ```

## Code Challenge
