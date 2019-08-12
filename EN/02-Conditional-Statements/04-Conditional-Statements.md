[slide]
# If Statement
One of the single most important statements in every programming language is the **if statement**.

An if statement identifies which statement to run based on the value of a **boolean expression**. 

In the following example, the bool variable condition is set to true and then checked in the **if** statement.

The if statement needs a boolean result, that is, **true or false**
  * If the boolean result is true, take action

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
# Variable Lifetime
Not all variables are accessible from all parts of our program, and not all variables exist for the same amount of time

Where a variable is accessible and how long it exists depend on how it is defined

A variable which is defined in the main body of a file is called a global variable

Here is an example of variables in different scopes:
```python
currentDay = "Monday"
if currentDay == "Monday":
    salary = 1000
print(salary)  # 1000
```

```python
currentDay = "Tuesday" 
if currentDay == "Monday":
    salary = 1000
print(salary)  # Error
```
[/slide]

[slide]
# Problem: Freezing Weather
[code-task title="Freezing Weather" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0
[/task-description]
[tests]
[test]
[input]
-5.5
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
32.8
[/input]
[output]
[/output]
[/test]
[test]
[input]
-10.6
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
-2.13
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
105
[/input]
[output]
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4||
|-2|Freezing weather!|
[/slide]

[slide]
# Solution: Freezing Weather
[code-task title="Freezing Weather" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
temperature = float(input())
if temperature <= 0:
   print("Freezing weather!")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a temperature in Celsius
* **Checks** whether the temperature is **below zero**
* Prints ***"Freezing weather!"***, if the temperature is equal or lower than 0
[/task-description]
[tests]
[test]
[input]
-5.5
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
32.8
[/input]
[output]
[/output]
[/test]
[test]
[input]
-10.6
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
-2.13
[/input]
[output]
Freezing weather!
[/output]
[/test]
[test]
[input]
105
[/input]
[output]
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4||
|-2|Freezing weather!|
[/slide]