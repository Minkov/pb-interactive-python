[slide]
# Homework
Now, it's your turn to practice what you have learned in the training session.

We have prepared some simple problems for you to solve. If you struggle you can see the solution after each problem. 
[/slide]

[slide]
# Problem: Welcome
[code-task title="Welcome" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Receives a single line: name
* Prints the following message: "Welcome, \{name\}"
[/task-description]
[code-io /]
[tests]
[test]
[input]
George
[/input]
[output]
Welcome, George
[/output]
[/test]
[test]
[input]
Pesho
[/input]
[output]
Welcome, Pesho
[/output]
[/test]
[test]
[input]
asd
[/input]
[output]
Welcome, asd
[/output]
[/test]
[test]
[input]
Ann
[/input]
[output]
Welcome, Ann
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|John|Welcome, John|
[/slide]

[slide]
# Solution: Welcome
[code-task title="Welcome" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
name = input()
print(f"Welcome, {name}")
```
[/code-editor]
[task-description]
Write a program, which:

* Receives a single line: name
* Prints the following message: "Welcome, \{name\}"
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|John|Welcome, John|
[/slide]

[slide]
# Problem: Area of Triangle
[code-task title="Area of Triangle" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Create a function that receives two numbers:

* The side of a triangle - a
* The height for that side - ha
* Print the area formatted to the 2nd digit
[/task-description]
[code-io /]
[tests]
[test]
[input]
12.0
2.0
[/input]
[output]
12.00
[/output]
[/test]
[test]
[input]
5.0
4.0
[/input]
[output]
10.00
[/output]
[/test]
[test]
[input]
10.5
2.5
[/input]
[output]
13.13
[/output]
[/test]
[test]
[input]
1.6
2.8
[/input]
[output]
2.24
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|25.00|
|10||
[/slide]

[slide]
# Solution: Area of Triangle
[code-task title="Area of Triangle" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
a = float(input())
h = float(input())
area = (a * h) / 2
print(f'{area:.2f}')
```
[/code-editor]
[task-description]
Create a function that receives two numbers:

* The side of a triangle - a
* The height for that side - ha
* Print the area formatted to the 2nd digit
[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|5|25.00|
|10||
[/slide]

[slide]
# Problem: Four Operations
[code-task title="Four Operations" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 parameters
* Performs the 4 arithmetic operations, in the following order: +, -, *, /
[/task-description]
[code-io /]
[tests]
[test]
[input]
10.0
5.0
[/input]
[output]
10.00 + 5.00 = 15.00
10.00 - 5.00 = 5.00
10.00 * 5.00 = 50.00
10.00 / 5.00 = 2.00
[/output]
[/test]
[test]
[input]
2.5
6.5
[/input]
[output]
2.50 + 6.50 = 9.00
2.50 - 6.50 = -4.00
2.50 * 6.50 = 16.25
2.50 / 6.50 = 0.38
[/output]
[/test]
[test]
[input]
10.5
2.5
[/input]
[output]
10.50 + 2.50 = 13.00
10.50 - 2.50 = 8.00
10.50 * 2.50 = 26.25
10.50 / 2.50 = 4.20
[/output]
[/test]
[test]
[input]
1.6
2.8
[/input]
[output]
1.60 + 2.80 = 4.40
1.60 - 2.80 = -1.20
1.60 * 2.80 = 4.48
1.60 / 2.80 = 0.57
[/output]
[/test]
[/tests]

[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|5|5 + 10 = 15| 
|10|5 - 10 = -5|
||5 * 10 = 50|
||5 / 10 = 0.5|
[/slide]

[slide]
# Solution: Four Operations
[code-task title="Four Operations" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
num1 = int(input())
num2 = int(input())
print(f'{num1} + {num2} = {num1 + num2}')
print(f'{num1} - {num2} = {num1 - num2}')
print(f'{num1} * {num2} = {num1 * num2}')
print(f'{num1} / {num2} = {num1 / num2}')
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 parameters
* Performs the 4 arithmetic operations, in the following order: +, -, *, /
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|5|5 + 10 = 15| 
|10|5 - 10 = -5|
||5 * 10 = 50|
||5 / 10 = 0.5|
[/slide]

[slide]
# Problem: Days to Minutes
[code-task title="Days to Minutes" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a single number (days)
* Converts the days to minutes 
* Prints the minutes
[/task-description]
[code-io /]
[tests]
[test]
[input]
6
[/input]
[output]
8640
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
14400
[/output]
[/test]
[test]
[input]
32
[/input]
[output]
46080
[/output]
[/test]
[test]
[input]
9
[/input]
[output]
12960
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|2|2880|
|5|7200|
[/slide]

[slide]
# Solution: Days to Minutes
[code-task title="Days to Minutes" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
days = int(input())
hours = days * 24
minutes = hours * 60
print(minutes)
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a single number (days)
* Converts the days to minutes 
* Prints the minutes
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|2|2880|
|5|7200|
[/slide]

[slide]
# Problem: Currency Converter
[code-task title="Currency Converter" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the dollars to be converted 
* Converts dollars to euro (the rate of dollars to euro is 0.88)
* Prints the converted value in euro
[/task-description]
[code-io /]
[tests]
[test]
[input]
10.0
[/input]
[output]
8.8
[/output]
[/test]
[test]
[input]
5.0
[/input]
[output]
4.4
[/output]
[/test]
[test]
[input]
25.5
[/input]
[output]
22.44
[/output]
[/test]
[test]
[input]
12.0
[/input]
[output]
10.56
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96| 
|87|76.56|
[/slide]

[slide]
# Solution: Currency Converter
[code-task title="Currency Converter" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
dollars = float(input())
euros = dollars * 0.88
print(euros)
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the dollars to be converted 
* Converts dollars to euro (the rate of dollars to euro is 0.88)
* Prints the converted value in euro
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|17|14.96| 
|87|76.56|
[/slide]

[slide]
# Problem: Circle Area and Perimeter
[code-task title="Circle Area and Perimeter" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
import math

# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the radius of a circle
* Calculates the area and perimeter of a circle
* Prints the calculated values formatted to the 2nd decimal
[/task-description]
[code-io /]
[tests]
[test]
[input]
12.0
[/input]
[output]
Area = 452.389342
Perimeter = 75.398224
[/output]
[/test]
[test]
[input]
10.0
[/input]
[output]
Area = 314.159265
Perimeter = 62.831853
[/output]
[/test]
[test]
[input]
5.5
[/input]
[output]
Area = 95.033178
Perimeter = 34.557519
[/output]
[/test]
[test]
[input]
9.4
[/input]
[output]
Area = 277.591127
Perimeter = 59.061942
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|7|Area = 153.93804002589985|
||Perimeter = 43.982297150257104|
[/slide]

[slide]
# Solution: Circle Area and Perimeter
[code-task title="Circle Area and Perimeter" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
import math

radius = float(input())
area = radius * radius * math.pi
perimeter = 2 * math.pi * radius
print(f'Area = {area}')
print(f'Perimeter = {perimeter}')
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the radius of a circle
* Calculates the area and perimeter of a circle
* Prints the calculated values formatted to the 2nd decimal
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output
|       Input       | Output |
|-------------------|--------|
|7|Area = 153.93804002589985|
||Perimeter = 43.982297150257104|
[/slide]

[slide]
# Problem: Inches to Centimeters
[code-task title="Inches to Centimeters" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the inches to be converted
* Calculates them to centimeters 
* Prints the result 
[/task-description]
[code-io /]
[tests]
[test]
[input]
10
[/input]
[output]
25.4
[/output]
[/test]
[test]
[input]
5
[/input]
[output]
12.7
[/output]
[/test]
[test]
[input]
15.5
[/input]
[output]
39.37
[/output]
[/test]
[test]
[input]
0.5
[/input]
[output]
1.27
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|21|53.34| 
|71|180.34|
[/slide]

[slide]
# Solution: Inches to Centimeters
[code-task title="Inches to Centimeters" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
inches = float(input())
centimeters = inches * 2.54
print(centimeters)
```
[/code-editor]
[task-description]
Write a function, which:

* Receives a number - the inches to be converted
* Calculates them to centimeters 
* Prints the result 
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|21|53.34 | 
|71|180.34|
[/slide]

[slide]
# Problem: Calculate Speed
[code-task title="Calculate Speed" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 numbers - distance and time
* Calculates the speed needed to travel a given distance for a given time
* Prints the calculated result
[/task-description]
[code-io /]
[tests]
[test]
[input]
10.0
2.0
[/input]
[output]
5.0
[/output]
[/test]
[test]
[input]
2.0
10.0
[/input]
[output]
0.2
[/output]
[/test]
[test]
[input]
4.0
5.0
[/input]
[output]
0.8
[/output]
[/test]
[test]
[input]
4.5
10.0
[/input]
[output]
0.45
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15|7.5| 
|2||
[/slide]

[slide]
# Solution: Calculate Speed
[code-task title="Calculate Speed" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
distance = float(input())
time = float(input())
speed = distance / time
print(speed)
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 2 numbers - distance and time
* Calculates the speed needed to travel a given distance for a given time
* Prints the calculated result
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|15|7.5| 
|2||
[/slide]

[slide]
# Problem: Person Info
[code-task title="Person Info" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 4 strings - first name, last name, country and town 
* Prints information about a person in the following format: "\{firstName\} \{lastName\} from \{country\} - \{town\}!"
[/task-description]
[code-io /]
[tests]
[test]
[input]
John
Smith
USA
LA
[/input]
[output]
John Smith from USA - LA!
[/output]
[/test]
[test]
[input]
Ann
Green
France
Paris
[/input]
[output]
Ann Green from France - Paris!
[/output]
[/test]
[test]
[input]
Pesho
Peshov
Bulgaria
Sofia
[/input]
[output]
Pesho Peshov from Bulgaria - Sofia!
[/output]
[/test]
[test]
[input]
A
B
C
D
[/input]
[output]
A B from C - D!
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Kelly|Kelly Smith from Ireland - Cork!|
|Smith||
|Ireland||
|Cork||
[/slide]

[slide]
# Solution: Person Info
[code-task title="Person Info" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
first_name = input()
last_name = input()
country = input()
town = input()
print(f'{first_name} {last_name} from {country} - {town}!')
```
[/code-editor]
[task-description]
Write a function, which:

* Receives 4 strings - first name, last name, country and town 
* Prints information about a person in the following format: "\{firstName\} \{lastName\} from \{country\} - \{town\}!"
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Kelly|Kelly Smith from Ireland - Cork!|
|Smith||
|Ireland||
|Cork||
[/slide]

[slide]
# Problem: Town Info
[code-task title="Town Info" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a function, which:

* Receives name (string), population and area (numbers)
* Prints information about a town in the following format: "Town \{name\} has population of \{population\} and area \{area\} square km."
[/task-description]
[code-io /]
[tests]
[test]
[input]
Sofia
100000
13000
[/input]
[output]
Town Sofia has population of 100000 and area 13000 square km.
[/output]
[/test]
[test]
[input]
Paris
20065
1200
[/input]
[output]
Town Paris has population of 20065 and area 1200 square km.
[/output]
[/test]
[test]
[input]
London
350000
1000
[/input]
[output]
Town London has population of 350000 and area 1000 square km.
[/output]
[/test]
[test]
[input]
A
123456
789
[/input]
[output]
Town A has population of 123456 and area 789 square km.
[/output]
[/test]
[/tests]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Berlin|Town Berlin has population of 3675000 and area 984 square km.|
|3675000||
|984||
[/slide]

[slide]
# Solution: Town Info
[code-task title="Town Info" executionStrategy="python-code" requiresInput]
[code-editor language="python"]
```
town_name = input()
population = int(input())
area = int(input())
print(f'Town {town_name} has population of {population} and area {area} square km.')
```
[/code-editor]
[task-description]
Write a function, which:

* Receives name (string), population and area (numbers)
* Prints information about a town in the following format: "Town \{name\} has population of \{population\} and area \{area\} square km."
[/task-description]
[code-io /]
[/code-task]

## Sample Input and Output

|       Input       | Output |
|-------------------|--------|
|Berlin|Town Berlin has population of 3675000 and area 984 square km.|
|3675000||
|984||
[/slide]
