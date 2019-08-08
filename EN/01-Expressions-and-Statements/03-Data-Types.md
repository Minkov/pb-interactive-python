[slide]
# Data Types
Variables can be used to hold different data types:

**int** - integer number : 1, 2, 3, 4 ….

**float** - real number : 0.5 , 3.14, -0.5 ….

**str** - string and chars : "a", "Hello", …

**bool** - boolean: True, False
[/slide]

[slide]
# Assigning Values to Variables
Python variables do not need explicit declaration to reserve memory space. 

The declaration happens automatically when you assign a value to a variable.

You can assign a **value** to a **variable** using **`=`**:
```python
first_num = 10
second_num = 5
first_num + second_num   # 15
```
The operand to the left of the **`=`** operator is the name of the variable and the operand to the right of the **`=`** operator is the value stored in the variable. 
[/slide]

[slide]
# Naming Conventions
In computer programming, a naming convention is a set of rules for choosing the name to be used for variables.

In Python the convention for naming variables is **"snake_case"**:
* Words consist only of **lowercase** letters
* Words are separated with **underscore** "_"
```python
this_is_correct
thisIsNotCorrect
This_Is_Not_Correct
This_is_also_not_correct
```

There are other conventions such as:
* Pascal Case - capitalizes each word, removes the space:
```python
FirstName = "Peter"
```

* Camel Case - similiar to Pascal Case but the first word is not capitalized:
```python
firstName = "Peter"
```
[/slide]

[slide]
# Data Types are Dynamic
In Python data types are dynamic.

Python variable assignment is different from some of the popular languages like C, C++ and Java. 

There is no declaration of a variable, just an assignment statement.

It doesn't know about the type of the variable until the code is run.

A single variable can be used to hold different data types:
```python
x = 5        # x is Number
x = "John"   # x is String
x = True     # x is Boolean
```
[/slide]

[slide]
# Strings
Strings are data types that can store text.

Assigning a string to a variable is done with the variable name followed by an equal sign and the string.

To set a string value to a variable you can use single or double quotes. 
```python
first_name = "John" 
last_name = 'Adams'
```
But you cannot use both together:
```python
first_name = 'John" 
# this will not work  
```
[/slide]

[slide]
# Comments
When writing code in **Python**, it's important to make sure that your code can be easily understood by others. 

Giving variables obvious names, defining explicit functions, and organizing your code are all great ways to do this.

Another easy way to increase the readability of your code is by using comments!

A comment is text in your program that is **not executed as a code**.

```python
# name = "John" <- this code will not be executed
```
[/slide]