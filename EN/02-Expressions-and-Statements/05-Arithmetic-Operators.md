[slide]
# Arithmetic Operations
Let's examine the basic **arithmetic operations** in programming. 

We can add, subtract, multiply and divide numbers using the operators `+`, `-`, `*` and `/`.

## Summing up Numbers
We can **sum** up numbers using the `+` operator:
```py live
a = 5;
b = 7;
sum = a + b;
print(sum); // 12 
```

## Subtracting Numbers
**Subtracting** numbers is done using the `-` operator:
```py live
a = 15;
b = 7;
print(a - b); // 8
```

## Multiplying Numbers
For **multiplication** of numbers we use the `*` operator:
```py live
a = 5;
b = 7;
print(a * b); // 35
```

## Dividing Numbers
**Dividing** numbers is done using the `/` and `//` operators. 

`/` does **floating point division**.
* Regardless of whether we divide two integers, floating point with integer or two floating points, the obtained output is **always floating point**.
 * Example: `5 / 2 = 2.5`

`//` is used for **floor division**.
* The result is a **floating point** number only if one of the operands is.
 * Example: `5 // 2.0 = 2.0`
* Otherwise the result is an **integer** number.
 * Example: `5 // 2 = 2`

Here are a few examples with the division operator:
```py live
a = 25
i = a / 4
print(i)
f = a // 4.0
print(f)
b = a // 4
print(b)
```

### Dividing Integers
Let's examine a few examples for **integer division** (remember that when we **divide integers** in C# the result is an **integer**):
```cs live
int a = 25;
Console.WriteLine(a / 4);
```

Dividing an integer by zero leads to an error.
``` cs live
int a = 5;
Console.WriteLine(a / 0);
```

### Dividing Floating-Point Numbers
Let's look at a few examples for **floating division**. 

When we divide floating point numbers, the result is always a **float number** and the division never fails.

It also works correctly with the special values **+∞** and **-∞**:
```cs live
int a = 15;
Console.WriteLine(a / 2.0);
Console.WriteLine(a / 0.0);
Console.WriteLine(-a / 0.0);
Console.WriteLine(0.0 / 0.0);
```

When printing the values ∞ and -∞, the console output may be `?`.

This happens because the console in Windows does not work correctly with Unicode and breaks most of the non-standard symbols, letters and special characters.

### Remainder
The remainder operator `%` computes the remainder after dividing its left-hand operand by its right-hand operand.
```cs live
int a = 7;
int b = 2;
Console.WriteLine(a % b);
Console.WriteLine(3.5 % 1);
```
It is useful if we want to check whether a number is **even** or **odd**.

If the remainder when dividing by 2 is equal to 0, then the number is even, otherwise it is odd.

See the following example: 
```cs live
Console.WriteLine(3 % 2);
Console.WriteLine(4 % 2);
```
[/slide]

[slide]
# Video

[vimeo-video videoId="341512905" startTimeInSeconds="5968" endTimeInSeconds="6610" /]

[/slide]
///////

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
```python
a = 25
b = 4
print(a / b) # 6.25
```
Modulo / remainder from integer division (operator **%**)
```python
print(3 % 2) # 1
print(4 % 2) # 0
print(3.5 % 1) # 0.5
```
[/slide]
