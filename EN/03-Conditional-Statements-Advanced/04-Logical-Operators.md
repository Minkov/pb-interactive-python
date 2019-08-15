[slide]
# Logical Operators
Logical Operators are used to perform the logical operation between two operands like **AND**, **OR** and **NOT** based on our requirements

The Logical Operators will **always work with Boolean expressions** (**true** or **false**) and return **Boolean values**

The logical operators are:
  * AND (**and**) - **returns true if both operands are true**
  * OR (**or**) - **returns true if any one operand is true**
  * Logical negation (**not**) - **returns the reverse of logical state**
    * Brackets **()** change the order

| Operand1 | Operand2 | and | or |
|---|---|---|---|
| True | True | True | True |
| True | False | False | True |
| False | True | False | True |
| False | False | False | False |

If you observe above table, **if any one operand value become false, then the logical `and` operator will return false**, same way **the logical `or` operator will return true, if any one operand value become true**

| Operand | not |
|---|---|
| true | false |
| false | true |

If you observe above table, **the `not` operator will always return the reverse value of operand** like **if operand value true, then the Logical NOT operator will return false and vice versa**
[/slide]

[slide]
# Problem: Bonus Points
[code-task title="Bonus Points" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program that applies bonus to given points
  * If points are between 0 and 3, adds 5
  * If points are between 4 and 6, adds 15
  * If points are between 7 and 9, adds 20
[/task-description]
[tests]
[test]
[input]
4
[/input]
[output]
19
[/output]
[/test]
[test]
[input]
8
[/input]
[output]
28
[/output]
[/test]
[test]
[input]
1
[/input]
[output]
6
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|19|
[/slide]

[slide]
# Solution: Bonus Points
[code-task title="Bonus Points" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
points = int(input())

if points >= 0 and points <= 3:
    points += 5
elif points >= 4 and points <= 6:
    points += 15
elif points >= 7 and points <= 9:
    points += 20

print(points)
```
[/code-editor]
[task-description]
Write a program that applies bonus to given points
  * If points are between 0 and 3, adds 5
  * If points are between 4 and 6, adds 15
  * If points are between 7 and 9, adds 20
[/task-description]
[tests]
[test]
[input]
4
[/input]
[output]
19
[/output]
[/test]
[test]
[input]
8
[/input]
[output]
28
[/output]
[/test]
[test]
[input]
1
[/input]
[output]
6
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|4|19|
[/slide]


[slide]
# Problem: Food or Drink
[code-task title="Food or Drink" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write code here
```
[/code-editor]
[task-description]
Write a program, which:
  * Reads single line and print "***drink***", "***food***" or "***unknown***"
  * Foods: curry, noodles, sushi, spaghetti 
  * Drinks: tea, water, coffee
  * Everything else is unknown
[/task-description]
[tests]
[test]
[input]
curry
[/input]
[output]
food
[/output]
[/test]
[test]
[input]
tea
[/input]
[output]
drink
[/output]
[/test]
[test]
[input]
something
[/input]
[output]
unknown
[/output]
[/test]
[/tests]
[/code-task]
[/slide]

[slide]
# Solution: Food or Drink
[code-task title="Food or Drink" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
input = input()
if input == "curry" or input == "noodles" or input == "sushi" or input == "spaghetti":
    print("food");
elif input == "tea" or input == "water" or input == "coffee":
    print("drink")
else:
    print("unknown")
```
[/code-editor]
[task-description]
Write a program, which:

  * Reads single line and print "***drink***", "***food***" or "***unknown***"
  * Foods: curry, noodles, sushi, spaghetti 
  * Drinks: tea, water, coffee
  * Everything else is unknown
[/task-description]
[tests]
[test]
[input]
curry
[/input]
[output]
food
[/output]
[/test]
[test]
[input]
tea
[/input]
[output]
drink
[/output]
[/test]
[test]
[input]
something
[/input]
[output]
unknown
[/output]
[/test]
[/tests]
[/code-task]
[/slide]