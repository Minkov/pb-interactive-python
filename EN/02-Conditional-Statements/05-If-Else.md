[slide]
# If...else Statement
In an if-else statement, **`if`** condition evaluates to **`true`**, the then-statement runs. If condition is false, the else-statement runs

Because condition can't be simultaneously true and false, the then-statement and the else-statement of an if-else statement can never both run

In an if statement that doesn't include an else statement, if condition is true, the then-statement runs. If condition is false, control is transferred to the next statement after the if statement.
 
```python
if ... :
  # then-statement
  # Commands to be executed if the condition is true
else:
  # else-statement
  # Commands to be executed if the condition is false
```

# Example: If...else Statement
```python
color = "red"
if color == "red":
   print("tomato")
   print("strawberry") 
else:
   print("banana")
   print("lemon")
```
[/slide]

[slide]
# Problem: Even or Odd
[code-task title="Even or Odd" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Checks whether a number is **even** or **odd**
* If it's **even**, it should print ***"even"***
* If it's **odd**, it should print ***"odd"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]

[slide]
# Solution: Even or Odd
[code-task title="Even or Odd" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num = int(input())
if num % 2 == 0: 
   print("even")
else:
   print("odd")
```
[/code-editor]
[task-description]
Write a program, which: 

* Checks whether a number is **even** or **odd**
* If it's **even**, it should print ***"even"***
* If it's **odd**, it should print ***"odd"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]