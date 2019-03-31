# EIP STEM-H Power Aid
## March 2, 2019

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (**Lunch**)
*  12:20 PM - 1:45 PM (PM Session)
*  1:45 PM (Leave)
*  1:50 PM - 2:00 PM (Departure)

### Installing Python 3 on Windows
  * [https://www.python.org/](https://www.python.org/)

### Installing Atom Editor on Windows
  *  [https://atom.io/](https://atom.io/)

### Review

  *  Launch the Windows Command Prompt ("cmd")
  *  Check that python is in your PATH by executing `python` in the Windows Command Prompt
     *  Exit the Windows Command Prompt after verifying
         * `exit()`
  *  Understanding the Windows Command Prompt
     *  Comparing with Windows Explorer

### Installing `script` package into Atom editor
  *  https://atom.io/packages/script
  *  Shortcut key: Ctrl + Shift + B

### Working with files

  *  How to read a file
  *  How to read a file piece by piece
  *  Writing files in Python
  *  Using the `with` operator

### I/O utilities in Python

## Opening a file

```python
file_object = open(file_name [, access_mode])
```

*  access_modes
    *  r
    *  r+
    *  w
    *  w+
    *  a
    *  a+

*  file object attributes
    *  file_object.closed
    *  file_object.mode
    *  file_object.name

*  file object methods
    *  `close()` - closes file object
    *  `write(string)` - writes a string to the file object
    *  `read()` - reads the entire contents of the file
    *  `readline()` - reads in a single line of the file

## Processing a file

### Using `for`

```python
for line in file_object:
    print(line)
```

### Using `with`

The with statement is used to wrap the execution of a block with methods defined by a context manager

```python
with open('filename.txt') as file_object:
    read_data = file_object.read()
```

## JSON - Javascript Object Notation

```python
import json

# files
json.load(data,filename)
json.dump(data,filename)

#strings
json.load()
json.dumps()
```

