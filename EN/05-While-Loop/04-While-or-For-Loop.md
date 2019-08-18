[slide]
# While or For Loop
`while` and `for` loops both **repeat** a block of **code**.

Sometime in programming we don't know in advance **how many times** to repeat a loop, neither we have a **clear loop condition**. In such cases, it is a good idea to **use** `while`  **loop** instead of `for` loop.

When you know **exactly how many times** you want to loop through a block of code, use the `for` loop instead of a `while` loop.
[/slide]

[slide]
# Problem: Odd Number
[code-task title="Odd Number" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads numbers from the console until it gets an **odd number**
* Prints the **odd** number
[/task-description]
[tests]
[test]
[input]
2
4
8
5
[/input]
[output]
5
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|3|
|4||
|8||
|3||
[/slide]

[slide]
# Solution: Odd Number
[code-task title="Odd Number" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
number = int(input())
while (number % 2) == 0:
    number = int(input())
print(number)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads numbers from the console until it gets an **odd number**
* Prints the **odd** number
[/task-description]
[tests]
[test]
[input]
2
4
8
5
[/input]
[output]
5
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|3|
|4||
|8||
|3||
[/slide]

[slide]
# Problem: Number Manipulator
[code-task title="Number Manipulator" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a number from the console
* Reads the following commands:
* **Add** - Аdds 1 to the number
* **Subtract** - Subtracts 1 from the number
* **END** -  Prints the number and stops the program
[/task-description]
[tests]
[test]
[input]
4
Add
END
[/input]
[output]
5
[/output]
[/test]
[test]
[input]
4
Subtract
END
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
4
Add
Add
Subtract
END
[/input]
[output]
5
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|6|
|Add||
|END||
[/slide]

[slide]
# Solution: Number Manipulator
[code-task title="Number Manipulator" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
number = int(input())
command = input()

while command != "END":
    if command == "Add":
        number += 1
    elif command == "Subtract":
        number -= 1
    command = input()
print(number)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads a number from the console
* Reads the following commands:
* **Add** - Аdds 1 to the number
* **Subtract** - Subtracts 1 from the number
* **END** -  Prints the number and stops the program
[/task-description]
[tests]
[test]
[input]
4
Add
END
[/input]
[output]
5
[/output]
[/test]
[test]
[input]
4
Subtract
END
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
4
Add
Add
Subtract
END
[/input]
[output]
5
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|6|
|Add||
|End||
[/slide]