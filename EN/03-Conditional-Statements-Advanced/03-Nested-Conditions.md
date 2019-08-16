[slide]
# Nested Conditions
Pretty often the program logic requires the use of if or if-else statements, which are **contained one inside another**. 

They are called **nested** if or if-else statements. 

As implied by the title "nested", these are ***if*** or ***if-else*** statements that are placed inside other ***if*** or ***else*** statements.

Only if the first condition is true the nested one is checked.

```python
if expression:
  if nested expression:
    # Code to be executed
  else:
    # Code to be executed
# Executes when the nested expression is false
```
**Deep nesting is not recommended**

Nesting of more than three conditional statements inside each other is not considered a good practice. 

It has to be avoided, mostly through optimization of the structure/the algorithm of the code and/or by using another type of conditional statement.

[/slide]

[slide]
# Problem: Marketplace
[code-task title="Marketplace" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Read a product and day from the console

Print the price, formatted to 2nd digit, based on the price list:

|Product|Weekday|Weekend|
|-------|-------|-------|
|Banana|2.50|2.70|
|Apple|1.30|1.60|
|Kiwi|2.20|3.00|
[/task-description]
[tests]
[test]
[input]
Banana
Weekday
[/input]
[output]
2.50
[/output]
[/test]
[test]
[input]
Apple
Weekend
[/input]
[output]
1.60
[/output]
[/test]
[test]
[input]
Kiwi
Weekend
[/input]
[output]
3.00
[/output]
[/test]
[test]
[input]
Apple
Weekday
[/input]
[output]
1.30
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Banana|2.50|
|Weekday||
[/slide]

[slide]
# Solution: Marketplace
[code-task title="Marketplace" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
product = input()
day_of_week = input()

if product == "Banana":
  if day_of_week == "Weekday":
    print("2.50")
  else:
    print("2.70")
elif product == "Apple":
  if day_of_week == "Weekday":
    print("1.30")
  else:
    print("1.60")
elif product == "Kiwi":
  if day_of_week == "Weekday":
    print("2.20")
  else:
    print("3.00")
```
[/code-editor]
[task-description]
Read a product and day from the console

Print the price, formatted to 2nd digit, based on the price list:

|Product|Weekday|Weekend|
|-------|-------|-------|
|Banana|2.50|2.70|
|Apple|1.30|1.60|
|Kiwi|2.20|3.00|
[/task-description]
[tests]
[test]
[input]
Banana
Weekday
[/input]
[output]
2.50
[/output]
[/test]
[test]
[input]
Apple
Weekend
[/input]
[output]
1.60
[/output]
[/test]
[test]
[input]
Kiwi
Weekend
[/input]
[output]
3.00
[/output]
[/test]
[test]
[input]
Apple
Weekday
[/input]
[output]
1.30
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|Banana|2.50|
|Weekday||
[/slide]

[slide]
# Problem: Biggest Number of Three
[code-task title="Biggest Number of Three" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads three integers
* Prints the biggest number
[/task-description]
[tests]
[test]
[input]
1
2
3
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
3
2
1
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
-2
0
4
[/input]
[output]
4
[/output]
[/test]
[test]
[input]
-10
-11
-12
[/input]
[output]
-10
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|3|
|2||
|3||

|Input|Output|
|-----|------|
|-1|-1|
|-5||
|-9||
[/slide]

[slide]
# Solution: Biggest Number of Three
[code-task title="Biggest Number of Three" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
first = int(input())
second = int(input())
third = int(input())
if first > second:
  if first > third:
    print(first)
  else:
    print(third)
else:
  if second > third:
    print(second)
  else:
    print(third)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads three integers
* Prints the biggest number
[/task-description]
[tests]
[test]
[input]
1
2
3
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
3
2
1
[/input]
[output]
3
[/output]
[/test]
[test]
[input]
-2
0
4
[/input]
[output]
4
[/output]
[/test]
[test]
[input]
-10
-11
-12
[/input]
[output]
-10
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|1|3|
|2||
|3||

|Input|Output|
|-----|------|
|-1|-1|
|-5||
|-9||
[/slide]

[slide]
# Video

[vimeo-video videoId="341568008" startTimeInSeconds="1121" endTimeInSeconds="2059" /]

[/slide]