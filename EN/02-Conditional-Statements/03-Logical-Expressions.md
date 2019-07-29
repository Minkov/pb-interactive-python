[slide]
# Comparison Operators
|Operators|Designation|
|---------|-----------|
| Equal to | == |
| Not Equal to | != |
| Greater than | \> |
| Greater than or equal to | \>= |
| Less than | \< |
| Less than or equal to | \<= |
[/slide]

[slide]
# Value Comparison
In programming we can **compare** values

  * The result of the logical expressions is either ***true*** or ***false***

Comparison operators can be used to construct expressions that compare the values of numeric variables. These expressions return a **boolean** value based on whether the comparison is true or false. 

Examples of such an expression are as follows.

```python
a = 5
b = 10
print(a < b)            # True
print(a > 100)          # False
print(a == '5')         # False
print(a <= 5)           # True
print(b == 2 * a)       # True
``` 
You can also compare numeric expressions. The expressions you compare can themselves be complex expressions, as in the following example.
```java
x / 45 * (y +17) >= math.sqrt(z) / (p - (x * 16))
```
The preceding complex expression includes literals, variables, and function calls. 

The expressions on both sides of the comparison operator are evaluated, and the resulting values are then compared using the >= comparison operator. 

If the value of the expression on the left side is greater than or equal to the value of the expression on the right, the entire expression evaluates to True; otherwise,it evaluates to False.

[/slide]


[slide]
# String Comparison
Comparing text using the equality operator \(==\). It compares two given strings based on the content of the string. 

If any character is not matched, it returns **false**. 

```python
a = 'Example';
b = 'Example2';
print(a == b)   // false
```

If all characters are matched or both of them are **null**, it returns **true**.

```python
a = "Example";
b = a;
print(a == b)   // true
```
```python
a = "5"
b = "5"
print(a == b)  // true 
```


[/slide]

