[slide]
# Simple Operations

# Concatenating Text and Numbers
In order to merge two strings into a single object, you may use the **“+”** operator. 

When the interpreter executes concatenation a new string will be created.

Examples:
```python
first_name = "John"
last_name = "Doe"
age = 34
text = first_name + " " + last_name + " | " + str(age)
print(text) # John Doe | 34
```
You can also concatenate integers.

```python
a = 5
b = 11
print(f'a + b = {a + b}')
# a + b = 511
``` 

One thing to note is that Python cannot concatenate a string and integer. 

These are considered two separate types of objects. So, if you want to merge the two, you will need to convert the integer to a string.
[/slide]

[slide]
# Arithmetic Operators
Arithmetic operators are used to perform **mathematical operations** like addition, subtraction, multiplication etc.

**Adding numbers** (operator `+`):
```python
a = 5
b = 7
sum = a + b
print(sum) # 12
```

**Subtracting numbers** (operator `-`):
```python
a = 15
b = 7
print(a - b) # 8
```

**Multiplying numbers** (operator `\*`):
```python
a = 5
b = 7
print(a * b) # 35
```

**Dividing numbers** (operator `\/`) works as a floor division in case all the arguments are integers. 

However, if one of the argument is float value the `\/` operator returns a float value.

Division poses a problem: if the expressions for both arguments happen to have an integral type, it implements floor division rather than true division.
```python
a = 25
b = 4
print(a / b) # 6.25
```

**Integer devision** (operator `\//`) returns floor value for both integer and floating point arguments. 

When the result of floor division (`\//`) is positive, it is as though the fractional portion is truncated off, leaving only the integer portion. 

When the result is negative, the result is rounded down to the next smallest (greater negative) integer.
```python
a = 5.0
b = 2
print(a // b) # 2.0
```

```python
a = -5.0
b = 2
print(a // b) # -3.0
```

**Modulo / remainder from integer division** (operator `%`) is used to get the reminder of a division. 

The basic syntax of **Python** Modulo is `a % b`. 

Here a is divided by b and the remainder of that division is returned.
```python
print(3 % 2) # 1
print(4 % 2) # 0
print(3.5 % 1) # 0.5
```
[/slide]