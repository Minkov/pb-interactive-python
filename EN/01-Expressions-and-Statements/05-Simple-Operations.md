[slide]
# Simple Operations

# Concatenating Text and Numbers
Examples:

```python
first_name = "John"
last_name = "Doe"
age = 34
text = first_name + " " + last_name + " | " + str(age)
print(text) # John Doe | 34
```
```python
a = 5
b = 11
print(f'a + b = {a + b}')
# a + b = 511
``` 
[/slide]

[slide]
# Arithmetic Operators
Adding numbers (operator **+**)
```python
a = 5
b = 7
sum = a + b
print(sum) # 12
```
Subtracting numbers (operator **-**)
```python
a = 15
b = 7
print(a - b) # 8
```
Multiplying numbers (operator **\***)
```python
a = 5
b = 7
print(a * b) # 35
```

Dividing numbers (operator **\/** )
The **\/** operator works as a floor division in case all the arguments are integers. However, if one of the argument is float value the **\/** operator returns a float value.
Division poses a problem: if the expressions for both arguments happen to have an integral type, it implements floor division rather than true division.
```python
a = 25
b = 4
print(a / b) # 6.25
```
Integer devision (operator **\//**)
It returns floor value for both integer and floating point arguments. When the result of floor division (//) is positive, it is as though the fractional portion is truncated off, leaving only the integer portion. When the result is negative, the result is rounded down to the next smallest (greater negative) integer:
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

Modulo / remainder from integer division (operator **%**)
```python
print(3 % 2) # 1
print(4 % 2) # 0
print(3.5 % 1) # 0.5
```
[/slide]

[slide]
# Video

[vimeo-video videoId="341528681" startTimeInSeconds="4533" endTimeInSeconds="4916" /]

[/slide]