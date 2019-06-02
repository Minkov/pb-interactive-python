[slide]
# If Statement
One of the single most important statements in every programming language is the if statement

The if statement needs a boolean result, that is, true or false
  * If the boolean result is true take action 

```python
if condition:
  # Code for execution if the condition is true
```
[/slide]

[slide]
# Indentation
Most of the programming languages like C, C++, Java use braces **\{** **\}** to define a block of code
  * **Python** uses indentation

A code block (body of a function, loop, if statement, etc.) **starts with indentation and ends with the first unindented line**

The amount of indentation is up to you, but it **must be consistent** throughout that block
  * Generally **four whitespaces** are used for indentation and is preferred over tabs 

The enforcement of indentation in **Python** makes the code look neat and clean
  * This results into **Python** programs that look **similar and consistent**

Here is an example:
```python
name = "John"
if name == "John": 
  print(name)
```

Indentation **can be ignored** in line continuation, **but it's a good idea to always indent**, because it makes the code more readable

For example:
```python
if True:
    print('Hello')
    a = 5
```

and

```python
if True: print('Hello'); a = 5
```

Both are valid and do the same thing, but the **former style is clearer and more readable**

Incorrect indentation will result into **`IndentationError`**:
```python
   name = "John"
if name == "John": 
  print(name)
# Indentation Error
```
[/slide]

[slide]
# Problem: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0, otherwise print ***"No output"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|No output|
|-2|Freezing weather!|
[/slide]

[slide]
# Solution: Freezing Weather
[code-task title="Freezing Weather" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
temperature = float(input())
if temperature <= 0:
   print("Freezing weather!")
else:
   print("No output")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0, otherwise print ***"No output"***
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|No output|
|-2|Freezing weather!|
[/slide]
