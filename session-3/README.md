# EIP STEM Fusion!
## February 29, 2019

### Instructor and Mentors

*  **Mr. Leang** (Instructor) 
*  **Jesse**

### Schedule

*  10:00 AM - 11:30 AM (AM Session)
*  11:35 AM - 12:15 PM (Lunch)
*  12:20 PM - 1:50 PM (PM Session)
*  1:50 PM - 2:00 PM (Departure)

### Questions / Comments

### Review
  *  How fast can you create a **hello.py** script which prints out `Hello World!` and run it?

### Installing Python 3 on Windows
  * [https://www.python.org/](https://www.python.org/)

### Installing Atom Editor on Windows
  *  [https://atom.io/](https://atom.io/)

### Installing an Integrated Development Environment (IDE) Visual Studio Code Community
  *  [https://code.visualstudio.com/](https://code.visualstudio.com/)

### Ensuring PATH environmnental variable is set
  * Google search terms [`environment variable setting windows 10`](https://www.google.com/search?num=100&q=environment+variable+setting+windows+10&spell=1&sa=X&ved=0ahUKEwjBhdSXq_3eAhXCo4MKHXdDBW8QBQgpKAA&biw=954&bih=1022)

### Control Structures
  *  Conditional Statements ([Review](https://github.com/eip-mason/intro-python/blob/master/session-2/README.md#programming-exercise-truth-table-for-booleans))

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

  *  ```python
     months_lists=['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec']
     ```

### Iterating over a dictionary

  *  ```python
     months_dictionary_1={
         1 : 'January',
         2 : 'February',
         3 : 'March',
         4 : 'April',
         5 : 'May',
         6 : 'June',
         7 : 'July',
         8 : 'August',
         9 : 'September',
         10: 'October',
         11: 'November',
         12: 'December' }
     ```
  
  *  ```python
     months_dictionary_2={
         'January'  :1 ,
         'February' :2 ,
         'March'    :3 ,
         'April'    :4 ,
         'May'      :5 ,
         'June'     :6 ,
         'July'     :7 ,
         'August'   :8 ,
         'September':9 ,
         'October'  :10,
         'November' :11,
         'December' :12}
     ```

### Iterating over a tuple

   *  ```python
      months_tuple=(
          "Jan",
          "Feburary",
          3,
          "Mar",
          "April",
          6,
          "Jul",
          "August",
          9,
          "Oct",
          "November",
          12
      )

### Programming exercise:

Beginner Task:

Given a list of values, iterate over the list of values and print the square of each value.

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
        values_squared=[]
        ...
        return values_squared

values=[1,2,3,4,5,6,7,8,9]
print(square_them(values))
```
