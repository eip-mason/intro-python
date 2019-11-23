# EIP STEM Fusion!
## November 23, 2019

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (**Lunch**)
*  12:20 PM - 1:50 PM (PM Session)
*  1:50 PM - 2:00 PM (Departure)

### Technology in the News

### Recap

*  Hello World!
    *  ATOM Editor
    *  Windows Command Prompt
        *  Add Python to your PATH
            *  `set PATH=%PATH%;C:\Python38`
        *  List directory contents
            *  `dir`
        *  Change into a `<directory>`
            *  `cd <directory>`
    *  Executing a Python script
        *  `python <source file>`

### Introduction to basic data types in Python

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

### None Python object

  *  None
  

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


