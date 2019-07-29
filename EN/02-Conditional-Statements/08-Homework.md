[slide]
# Homework
Now, it's your turn to practice what you have learned in the training session.

We have prepared some simple problems for you to solve. If you struggle you can see the solution after each problem. 
[/slide]

[slide]
# Problem: Guess the Password
[code-task title="Guess the Password" taskId="p-01" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program which:

* Reads a string that is a **password**
* Prints ***"Welcome"*** if the password is ***"s3cr3t!"***
* Prints ***"Wrong password!"*** in all other cases 
[/task-description]
[tests]
[test]
[input]
s3cr3t!
[/input]
[output]
Welcome
[/output]
[/test]
[test]
[input]
qwerty
[/input]
[output]
Wrong password!
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|s3cr3t!|Welcome|
|qwerty|Wrong password!|
[/slide]

[slide]
# Solution: Guess the Password
[code-task title="Guess the Password" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
password = input()
if password == "s3cr3t!":
  print("Welcome")
else:
  print("Wrong password!")
```
[/code-editor]
[task-description]
Write a program which:

* Reads a string that is a **password**
* Prints ***"Welcome"*** if the password is ***"s3cr3t!"***
* Prints ***"Wrong password!"*** in all other cases 
[/task-description]
[tests]
[test]
[input]
s3cr3t!
[/input]
[output]
Welcome
[/output]
[/test]
[test]
[input]
qwerty
[/input]
[output]
Wrong password!
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|s3cr3t!|Welcome|
|qwerty|Wrong password!|
[/slide]

[slide]
# Problem: Boiling Water
[code-task title="Boiling Water" taskId="p-02" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a floating-point number 
* Prints ***"The water is boiling"*** if the number **> 100**
* Prints ***"The water is not hot enough"*** in all other cases
[/task-description]
[tests]
[test]
[input]
104.8
[/input]
[output]
The water is boiling
[/output]
[/test]
[test]
[input]
29
[/input]
[output]
The water is not hot enough
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|104.8|The water is boiling|
|29|The water is not hot enough|
[/slide]

[slide]
# Solution: Boiling Water
[code-task title="Boiling Water" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
degrees = float(input())
if degrees > 100:
  print("The water is boiling") 
else :
  print("The water is not hot enough")
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a floating-point number 
* Prints ***"The water is boiling"*** if the number **> 100**
* Prints ***"The water is not hot enough"*** in all other cases
[/task-description]
[tests]
[test]
[input]
104.8
[/input]
[output]
The water is boiling
[/output]
[/test]
[test]
[input]
29
[/input]
[output]
The water is not hot enough
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|104.8|The water is boiling|
|29|The water is not hot enough|
[/slide]

[slide]
# Problem: Speed Info
[code-task title="Speed Info" taskId="p-03" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a floating-point number 
* Prints ***"Slow"*** if the number **<=** 30
* Prints ***"Fast"*** if the number **>** 30
[/task-description]
[tests]
[test]
[input]
30
[/input]
[output]
Slow
[/output]
[/test]
[test]
[input]
60
[/input]
[output]
Fast
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|30|Slow|
|60|Fast|
[/slide]

[slide]
# Solution: Speed Info
[code-task title="Speed Info" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
speed = float(input())
if speed <= 30:
  print("Slow")
else :
  print("Fast")
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a floating-point number 
* Prints ***"Slow"*** if the number **<=** 30
* Prints ***"Fast"*** if the number **>** 30
[/task-description]
[tests]
[test]
[input]
30
[/input]
[output]
Slow
[/output]
[/test]
[test]
[input]
60
[/input]
[output]
Fast
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|30|Slow|
|60|Fast|
[/slide]

[slide]
# Problem: Area of Figures
[code-task title="Area of Figures" taskId="p-04" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
import math

# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a type of figure 
* Reads a **number** (**two** numbers for **rectangle**)
* Checks if the figure is **square**, **rectangle** or **circle**
* Prints the calculated area **formatted** to the **second decimal**
* For unknown figure print **"Unknown figure"**

[/task-description]
[tests]
[test]
[input]
square
5
[/input]
[output]
25.00
[/output]
[/test]
[test]
[input]
rectangle
5
10
[/input]
[output]
50.00
[/output]
[/test]
[test]
[input]
circle
2.5
[/input]
[output]
19.63
[/output]
[/test]
[test]
[input]
figure
[/input]
[output]
Unknown figure
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|square|25.00|
|5||
[/slide]

[slide]
# Solution: Area of Figures
[code-task title="Area of Figures" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
import math

figure = input()
area = 0
if figure == "square":
  side = float(input())
  area = side * side
  print(f'{area:.2f}')
elif figure == "rectangle":
  width = float(input())
  height = float(input())
  area = width * height
  print(f'{area:.2f}')
elif figure == "circle":
  radius = float(input())
  area = math.pi * radius * radius
  print(f'{area:.2f}')
else:
  print("Unknown figure")
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a type of figure 
* Reads a **number** (**two** numbers for **rectangle**)
* Checks if the figure is **square**, **rectangle** or **circle**
* Prints the calculated area **formatted** to the **second decimal**
* For unknown figure print **"Unknown figure"**

[/task-description]
[tests]
[test]
[input]
square
5
[/input]
[output]
25.00
[/output]
[/test]
[test]
[input]
rectangle
5
10
[/input]
[output]
50.00
[/output]
[/test]
[test]
[input]
circle
2.5
[/input]
[output]
19.63
[/output]
[/test]
[test]
[input]
figure
[/input]
[output]
Unknown figure
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|square|25.00|
|5||
[/slide]

[slide]
# Problem: Tickets
[code-task title="Tickets" taskId="p-05" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program which:

* Reads a **ticket type** - either student or regular
* Prints the price in the following format "$\{price\}":
    * Student ticket is **1.60**
    * Regular ticket is **1.00**
    * For invalid type **"Invalid ticket type!"**
[/task-description]
[tests]
[test]
[input]
student
[/input]
[output]
$1.00
[/output]
[/test]
[test]
[input]
regular
[/input]
[output]
$1.60
[/output]
[/test]
[test]
[input]
ticket
[/input]
[output]
Invalid ticket type!
[/output]
[/test]
[/tests]
[/code-task]
[/slide]

[slide]
# Solution: Tickets
[code-task title="Tickets" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
ticket_type = input()
if ticket_type == "student":
    print("$1.00")
elif ticket_type == "regular":
    print("$1.60")
else:
    print("Invalid ticket type!")
```
[/code-editor]
[task-description]
Write a program which:

* Reads a **ticket type** - either student or regular
* Prints the price in the following format "$\{price\}":
    * Student ticket is **1.60**
    * Regular ticket is **1.00**
    * For invalid type **"Invalid ticket type!"**
[/task-description]
[tests]
[test]
[input]
student
[/input]
[output]
$1.00
[/output]
[/test]
[test]
[input]
regular
[/input]
[output]
$1.60
[/output]
[/test]
[test]
[input]
ticket
[/input]
[output]
Invalid ticket type!
[/output]
[/test]
[/tests]
[/code-task]
[/slide]

[slide]
# Problem: Coffee Shop
[code-task title="Coffee Shop" taskId="p-06" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **order** - either **"coffee"** or **"tea"**
* Reads an **extra** - either **"sugar"** or **"no"**
* Prints a price in format "Final price: $\{price\}", the price should be formatted to 2nd digit after the decimal point
    * Price for coffee - 1.00
    * Price for tea - 0.60
    * Price for the sugar - 0.40
[/task-description]
[tests]
[test]
[input]
coffee
sugar
[/input]
[output]
Final price: $1.40
[/output]
[/test]
[test]
[input]
coffee
no
[/input]
[output]
Final price: $1.00
[/output]
[/test]
[test]
[input]
tea
sugar
[/input]
[output]
Final price: $1.00
[/output]
[/test]
[test]
[input]
tea
no
[/input]
[output]
Final price: $0.60
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|coffee|$1.40|
|sugar||
|tea|$0.60|
|no||
[/slide]

[slide]
# Solution: Coffee Shop
[code-task title="Coffee Shop" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
order = input()
extra = input()
price = 0
if order == "coffee":
    price = 1.00
elif order == "tea":
    price = 0.60
if extra == "sugar":
    price = price + 0.40
print(f"Final price: ${price:.2f}")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **order** - either **"coffee"** or **"tea"**
* Reads an **extra** - either **"sugar"** or **"no"**
* Prints a price in format "Final price: $\{price\}", the price should be formatted to 2nd digit after the decimal point
    * Price for coffee - 1.00
    * Price for tea - 0.60
    * Price for the sugar - 0.40
[/task-description]
[tests]
[test]
[input]
coffee
sugar
[/input]
[output]
Final price: $1.40
[/output]
[/test]
[test]
[input]
coffee
no
[/input]
[output]
Final price: $1.00
[/output]
[/test]
[test]
[input]
tea
sugar
[/input]
[output]
Final price: $1.00
[/output]
[/test]
[test]
[input]
tea
no
[/input]
[output]
Final price: $0.60
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|coffee|$1.40|
|sugar||
|tea|$0.60|
|no||
[/slide]

[slide]
# Problem: Valid Triangle
[code-task title="Valid Triangle" taskId="p-07" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Receives **3 integers** - the **sides** of a **triangle**
* Checks if each side is lesser than the **sum** of the **other 2**
* Prints ***"Valid Triangle"*** if the above condition is met
* Prints ***"Invalid Triangle"*** otherwise 
[/task-description]
[tests]
[test]
[input]
3
4
5
[/input]
[output]
Valid Triangle
[/output]
[/test]
[test]
[input]
5
8
3
[/input]
[output]
Invalid Triangle
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3|Valid Triangle|
|4||
|5||
[/slide]

[slide]
# Solution: Valid Triangle
[code-task title="Valid Triangle" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
a = int(input())
b = int(input())
c = int(input())
is_valid_triangle = True
if a + b <= c:
  is_valid_triangle = False
elif a + c <= b:
  is_valid_triangle = False
elif b + c <= a:
  is_valid_triangle = False
if is_valid_triangle:
  print("Valid Triangle")
else:
  print("Invalid Triangle")
```
[/code-editor]
[task-description]
Write a program, which:

* Receives **3 integers** - the **sides** of a **triangle**
* Checks if each side is lesser than the **sum** of the **other 2**
* Prints ***"Valid Triangle"*** if the above condition is met
* Prints ***"Invalid Triangle"*** otherwise 
[/task-description]
[tests]
[test]
[input]
3
4
5
[/input]
[output]
Valid Triangle
[/output]
[/test]
[test]
[input]
5
8
3
[/input]
[output]
Invalid Triangle
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|3|Valid Triangle|
|4||
|5||
[/slide]

[slide]
# Problem: Sum of Numbers
[code-task title="Sum of Numbers" taskId="p-09" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Receives **3 numbers**
* Prints ***"True"*** if the **sum** of **2** of them is **equal** to the **third one**
* Prints ***"False"*** if the condition above is **NOT met**
[/task-description]
[tests]
[test]
[input]
3
4
7
[/input]
[output]
True
[/output]
[/test]
[test]
[input]
5
8
3
[/input]
[output]
True
[/output]
[/test]
[test]
[input]
3
4
1
[/input]
[output]
False
[/output]
[/test]
[test]
[input]
5
8
100
[/input]
[output]
False
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|True|
|6||
|4||

|Input|Output|
|-----|------|
|0|False|
|2||
|3||
[/slide]

[slide]
# Solution: Sum of Numbers
[code-task title="Sum of Numbers" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num1 = int(input())
num2 = int(input())
num3 = int(input())
if num1 + num2 == num3:
  print(True)
elif num1 + num3 == num2:
  print(True)
elif num2 + num3 == num1:
  print(True)
else:
  print(False)
```
[/code-editor]
[task-description]
Write a program, which:

* Receives **3 numbers**
* Prints ***"True"*** if the **sum** of **2** of them is **equal** to the **third one**
* Prints ***"False"*** if the condition above is **NOT met**
[/task-description]
[tests]
[test]
[input]
3
4
7
[/input]
[output]
True
[/output]
[/test]
[test]
[input]
5
8
3
[/input]
[output]
True
[/output]
[/test]
[test]
[input]
4
6
15
[/input]
[output]
False
[/output]
[/test]
[test]
[input]
5
8
100
[/input]
[output]
False
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|2|True|
|6||
|4||

|Input|Output|
|-----|------|
|0|False|
|2||
|3||
[/slide]
