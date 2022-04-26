# Feedback: Assessment Task 1

*55-502605: Programming with Mathematical Applications* (2021-22)  
Peter Rowlett

Student: Ella Hollingshead (b9038879)

## Overall feedback

The work provided shows some promise and has some aspects correct, showing ability with program code in some areas. Substantial parts of the assignment are not attempted, often the more difficult parts.

## Overall grade

Low 3

## Detailed feedback (some automated)

**Manual fixes made for programs to run**: None needed.

### 1 Python

**Python syntax issues**: None found.

**Q1**: Doesn't return value, prints instead. Numbers don't all work. This is because your line `h % 3 == 0` tests whether `h` is divisible by 3, but earlier you already saved over `h` with `h=h/3`, so you are testing whether `h/3` is divisible by 3. Does attempt to deal with incorrect input.

**Q2**: Doesn't return value, prints instead. Doesn't always return square root, e.g. for input -16 returns "Please make sure you input a number".

**Q3**: Doesn't return value, prints instead. On division by zero, sends standard, unchecked ZeroDivisionError message. Something more user-friendly would be better for failing gracefully. Doesn't deal with poor input, e.g. input 'Peter' halts and throws an exception with message "invalid literal for int() with base 10: 'Peter'".

**Q4**: Not answered

**Q5**: Not answered

**Printed output** (coursework brief said 'It should not output otherwise, e.g. via print.'):

```
132.0
None
False
False
True
False
False
True
False
False
True
False
False
True
Please make sure you input a number between 1 and 100
Please make sure you input a number between 1 and 100
Please make sure you input a number between 1 and 100
3.0
3.0
Please make sure you input a number
0.0
Please make sure you input a number
132.0
113.6
8.0
```

**Result of running help() on submission file**:

```
Python Library Documentation: module b9038879

NAME
    b9038879

DESCRIPTION
    The following code is for question 1
    It lets the user input a value (h) and works out if it is a multiple of 3
    If it is the program will output 'True'
    If it isn't the program will output 'False'

FUNCTIONS
    question1(h)

    question2(i)

    question3(j)

FILE
    /home/.../b9038879.py
```


### 2 Databases

No part works with the code as given. For Q1 the SELECT queries have multiple errors. For Q2 and Q3 it is just that the wrong table name is used, when this is fixed the queries work as expected. Q4 not provided.

### 3 Documentation

README is good except missing user guide. Documentation strings are sometimes good, though should be inside the functions they are about. Code comments are correct but over the top, these should be used sparingly as needed.

### 4 Reflection on weekly tasks

Reflections describe how difficult tasks were found rather than reflecting on what was learned, and do not cover all tasks.
