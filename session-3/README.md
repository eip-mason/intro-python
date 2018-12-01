# EIP STEM-H Power Aid
## December 1, 2018

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (Lunch - Thompson L004)
*  12:20 PM - 1:50 PM (PM Session)
*  1:50 PM - 2:00 PM (Departure)

### Installing Python 3 on Windows
  * [https://www.python.org/](https://www.python.org/)

### Installing Atom Editor on Windows
  *  [https://atom.io/](https://atom.io/)

### Installing an Integrated Development Environment (IDE) Visual Studio Code Community
  *  [https://code.visualstudio.com/](https://code.visualstudio.com/)

### Ensuring PATH environmnental variable is set
  * Google search terms [`environment variable setting windows 10`](https://www.google.com/search?num=100&q=environment+variable+setting+windows+10&spell=1&sa=X&ved=0ahUKEwjBhdSXq_3eAhXCo4MKHXdDBW8QBQgpKAA&biw=954&bih=1022)

### Control Structures
  *  Conditional Statements

        ```python
        # if-statement
        shoe="RED"
        if (shoe == "RED"):
            print("Shoe is RED")
        
        # if-else statement
        shoe="BLACK"
        if (shoe == "RED"):
            print("Shoe is RED")
        else:
            print("Shoe is NOT RED")
    
        # if-elif statement
        shoe="GREEN"
        if (shoe == "RED"):
            print("Shoe is RED")
        elif (shoe == "BLACK"):
            print("Shoe is BLACK")
        
        # if-elif-else statement
        shoe="GREEN"
        if (shoe == "RED"):
            print("Shoe is RED")
        elif (shoe == "BLACK"):
            print("Shoe is BLACK")
        else:
            print("Shoe is NEITHER RED NOR BLACK")
        ```

  *  For Loop (iterate over any sequence)

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
        range([start], stop[, step])
        # start: starting number of sequence
        # stop: generate numbers up to, but not including this number
        # step: difference between each number in the sequence
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

  *  While Loop (repeated execution when expression is `True`
  

        ```python
        # while-statement
        maxValue=50
        x=0
        while (x < maxValue):
            x=x+1
            print(x,"is less than max")
        print(x,"is NOT less than max")
        ```

### Iterating over a list

### Iterating over a dictionary

### Iterating over a tuple

### Functions

  *  Definition and use
  *  Arguments
  *  Block structure
  *  Scope and globals
  
### API (application programming interface)

### Programming exercise:

Beginner Task:

Given a list of values, each value of the list squared.

```python
values=[1,2,3,4,5,6,7,8,9]
...
```

Intermediate Task:

Define a function `square_them` that takes in a list of numbers as a parameter and returns a list with each element squared.


```python

def square_them(values=None):
    if values is None:
        return
    else:
        ...

values=[1,2,3,4,5,6,7,8,9]
print(square_them(values))
```
