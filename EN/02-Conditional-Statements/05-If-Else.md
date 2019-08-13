[slide]
# If...else Statement

In an if-else statement, **`if`** condition evaluates to **`true`**, the then-statement runs. 
If the condition is false, the else-statement runs.

Because a condition can’t be simultaneously `true` and `false`, the then-statement and the else-statement of an if-else statement can never both run. 

After the then-statement or the else-statement runs, control is transferred to the next statement after the if statement.

In an **if** statement that doesn’t include an **else** statement, if the condition is **`true`**, the then-statement runs. 

If the condition is **`false`**, control is transferred to the next statement after the if statement.

Both the then-statement and the else-statement can consist of a single statement or multiple statements that are enclosed in braces: `{ }`. 

For a single statement, the braces are **optional** but recommended.

The statement or statements in the then-statement and the else-statement can be of any kind, including another if statement **nested** inside the original if statement.
 
```python
if condition:
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
[code-task title="Even or Odd" executionType="tests-execution" executionStrategy="python-code" requiresInput]
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
[tests]
[test]
[input]
4
[/input]
[output]
even
[/output]
[/test]
[test]
[input]
7
[/input]
[output]
odd
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
even
[/output]
[/test]
[test]
[input]
91
[/input]
[output]
odd
[/output]
[/test]
[test]
[input]
105
[/input]
[output]
odd
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]

[slide]
# Solution: Even or Odd
[code-task title="Even or Odd" executionType="tests-execution" executionStrategy="python-code" requiresInput]
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
[tests]
[test]
[input]
4
[/input]
[output]
even
[/output]
[/test]
[test]
[input]
7
[/input]
[output]
odd
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
even
[/output]
[/test]
[test]
[input]
91
[/input]
[output]
odd
[/output]
[/test]
[test]
[input]
105
[/input]
[output]
odd
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|even|
|7|odd|
[/slide]

[slide]
# Video

[vimeo-video videoId="341553633" startTimeInSeconds="2429" endTimeInSeconds="2553" /]

[/slide]