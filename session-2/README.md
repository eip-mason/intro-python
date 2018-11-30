# EIP STEM-H Power Aid
## November 17, 2018

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**
*  **Powlos**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (Lunch - Johnson Center)
*  12:20 PM - 1:50 PM (PM Session)
*  1:50 PM - 2:00 PM (Departure)

### Technology in the News

*  Amazon announces HQ2 locations (Nothern Virginia)
    *  What is Amazon?
    *  What is Cloud Computing?
    *  Why is this a big deal?
    *  What does this mean to you as a student in/graduating high school?
    *  What should you do if you are interested in working for Amazon?

### Recap

*  Hello World!
    *  ATOM Editor
    *  Windows Command Prompt
        *  Add Python to your PATH
            *  `set PATH=%PATH%;C:\Python34`
        *  List directory contents
            *  `dir`
        *  Change into a `<directory>`
            *  `cd <directory>`
    *  Executing a Python script
        *  `python <source file>`

## Session 2 : Saturday, November 17, 2018

### Introduction to basic data types in Python

  *  None
  *  string (an array/list of characters)
  *  int
  *  float
  *  boolean
  *  list : `[]`
      *  append()
      *  len()
      *  min()
      *  max()
      *  ...
  *  tuple : `()` - (an immutable list)
      *  count()
      *  index()
  *  dictionary : `{}` - (key/value pairs)

### Typecasting

  *  `myNumber = 4.25`
      *  `int(myNumber)`
  *  `myNumber = 4`
      *  `float(myNumber)`
  *  Usage and pitfalls
  
### Strings

  *  Concatenation (addition)
     *  `newString = myString1 + myString2`
  *  Methods
     *  `lower()`
     *  `upper()`
     *  `swapcase()`
     *  `strip()`
     *  `replace()`
  *  Slicing (`string = "Hellow World and EIP!"`)
     *  `string[10:]` = `'ld and EIP!'`
     *  `string[:10]` = `'Hellow Wor'`
     *  `string[:]` = `'Hellow World and EIP!'`
     *  `string[:10]+string[10:]` = `'Hellow World and EIP!'`
     *  `string[-5:]` = `' EIP!'`
     *  `string[:-5]` = `'Hellow World and'`

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
|`True`||`not P`|`not True` = `False`|
|`False`||`not P`|`not False` = `True`|
|`True`|`True`|`P or Q`|`True or True` = `True`|
|`True`|`False`|`P or Q`|`True or False` = `True`|
|`False`|`True`|`P or Q`|`False or True` = `True`|
|`False`|`False`|`P or Q`|`False or False` = `False`|
|`True`|`True`|`P and Q`|`True and True` = `True`|
|`True`|`False`|`P and Q`|`True and False` = `False`|
|`False`|`True`|`P and Q`|`False and True` = `False`|
|`False`|`False`|`P and Q`|`False and False` = `False`|
|`True`|`True`|`not (P or Q)`|`not (True or True)` = `not (True)` = `False`|
|`True`|`False`|`not (P or Q)`|`not (True or False)` = `not (True)` = `False`|
|`False`|`True`|`not (P or Q)`|`not (False or True)` = `not (True)` = `False`|
|`False`|`False`|`not (P or Q)`|`not (False or False)` = `not (False)` = `True`|
|`True`|`True`|`not (P and Q)`|`not (True and True)` = `not (True)` = `False`|
|`True`|`False`|`not (P and Q)`|`not (True and False)` = `not (False)` = `True`|
|`False`|`True`|`not (P and Q)`|`not (False and True)` = `not (False)` = `True`|
|`False`|`False`|`not (P and Q)`|`not (False and False)` = `not (False)` = `True`|
|`1`|`1`|`P == Q`|`True`|
|`1`|`0`|`P == Q`|`False`|
|`0`|`1`|`P == Q`|`False`|
|`0`|`0`|`P == Q`|`True`|
|`1`|`1`|`P != Q`|`True`|
|`1`|`0`|`P != Q`|`True`|
|`0`|`1`|`P != Q`|`True`|
|`0`|`0`|`P != Q`|`False`|


