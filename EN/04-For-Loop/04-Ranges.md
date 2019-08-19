[slide]
# Range
To loop through a set of code a specified number of times, we can use the `range()` function.

The `range()` function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number.

Note that range(6) is not the values of 0 to 6, but the values 0 to 5:
```py
for x in range(6):
  print(x)
```

The `range()` function defaults to 0 as a starting value, however it is possible to specify the starting value by adding a parameter: `range(2, 6)`, which means values from 2 to 6 (but not including 6):
```python
for x in range(2, 6):
  print(x)
```

The `range()` function defaults to increment the sequence by 1, however it is possible to specify the increment value by adding a third parameter: `range(2, 30, 3)`:
```python
for x in range(2, 30, 3):
  print(x)
```
[/slide]

[slide]
# Problem: Print Sum of N Numbers
[code-task title="Print Sum of N Numbers" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads number n from the console
* Sums all numbers from 1 to n
* Prints the sum on the console
[/task-description]
[tests]
[test]
[input]
7
[/input]
[output]
28
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|15|
|6|21|
[/slide]

[slide]
# Solution: Print Sum of N Numbers
[code-task title="Print Sum of N Numbers" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
n = int(input())
sum = 0
for i in range(1, n + 1):
   sum += i
print(sum)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads number n from the console
* Sums all numbers from 1 to n
* Prints the sum on the console
[/task-description]
[tests]
[test]
[input]
7
[/input]
[output]
28
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|15|
|6|21|
[/slide]

[slide]
# Problem: Calculate Monthly Salary
[code-task title="Calculate Monthly Salary" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads working days in the current month and salary for each day
* Calculates the salary for the month
* Prints the result on the console
[/task-description]
[tests]
[test]
[input]
3
100
200
300
[/input]
[output]
600
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|30|300|
|10||

|Input|Output|
|-----|------|
|3|330|
|100||
|110||
|120||
[/slide]

[slide]
# Solution: Calculate Monthly Salary
[code-task title="Calculate Monthly Salary" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
days = int(input())
total_salary = 0
for i in range(1, days + 1):
  salary_per_day = int(input())
  total_salary += salary_per_day
print(total_salary)
```
[/code-editor]
[task-description]
Write a program, which:

* Reads working days in the current month and salary for each day
* Calculates the salary for the month
* Prints the result on the console
[/task-description]
[tests]
[test]
[input]
3
100
200
300
[/input]
[output]
600
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3|330|
|100||
|110||
|120||
[/slide]