[slide]
# Problem: Guess the Password
[code-task title="Guess the Password" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|s3cr3t!|Welcome|
|qwerty|Wrong password!|
[/slide]

[slide]
# Problem: Boiling Water
[code-task title="Boiling Water" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
if degrees > 100 :
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
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|104.8|The water is boiling|
|29|The water is not hot enough|
[/slide]

[slide]
# Problem: Speed Info
[code-task title="Speed Info" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|30|Slow|
|60|Fast|
[/slide]

[slide]
# Problem: Area of Figures
[code-task title="Area of Figures" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a type of figure 
* Reads a **number** (**two** numbers for **rectangle**)
* Checks if the figure is **square**, **rectangle** or **circle**
* Prints the calculated area **formatted** to the **second decimal**

[/task-description]
[code-io /]
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
  area = width * heihgt
  print(f'{area:.2f}')
elif figure == "circle":
  radius = float(input())
  area = math.pi * radius * radius
  print(f'{area:.2f}')
```
[/code-editor]
[task-description]
Write a program, which: 

* Reads a type of figure 
* Reads a **number** (**two** numbers for **rectangle**)
* Checks if the figure is **square**, **rectangle** or **circle**
* Prints the calculated area **formatted** to the **second decimal**

[/task-description]
[code-io /]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|square|25.00|
|5||
[/slide]

[slide]
# Problem: Tickets
[code-task title="Tickets" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
else :
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
[code-io /]
[/code-task]
[/slide]

[slide]
# Problem: Coffee Shop
[code-task title="Coffee Shop" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **order** - either **"coffee"** or **"tea"**
* Reads an **extra** - either **"sugar"** or **"no"**
* Prints a price in format "Final price: $\{price\}"
    * Price for coffee - 1.00
    * Price for tea - 0.60
    * Price for the sugar - 0.40
[/task-description]
[code-io /]
[/code-task]
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
  price += 0.40
print(f"Final price: {price}")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **order** - either **"coffee"** or **"tea"**
* Reads an **extra** - either **"sugar"** or **"no"**
* Prints a price in format "Final price: $\{price\}"
    * Price for coffee - 1.00
    * Price for tea - 0.60
    * Price for the sugar - 0.40
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Problem: Frozen Fire
[code-task title="Frozen Fire" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 positive numbers
* Calculates the **differences** between:
    * The **1st** and the **2nd** number - as **n**
    * The **2nd** and the **3rd** number - as **p**

* Prints ***"Ice prevails"*** if **n** is greater than p
* Prints ***"Fire prevails"*** if **p** is greater than n
* Prints ***"Frozen Fire"*** if they are **equal**
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Solution: Frozen Fire
[code-task title="Frozen Fire" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
ice = float(input())
catalyst = float(input())
fire = float(input())
n = ice - catalyst
p = catalyst - fire
if n > p:
  print("Ice prevails")
elif n < p:
  print("Fire prevails")
else:
  print("Frozen fire")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads 3 positive numbers
* Calculates the **differences** between:
    * The **1st** and the **2nd** number - as **n**
    * The **2nd** and the **3rd** number - as **p**

* Prints ***"Ice prevails"*** if **n** is greater than p
* Prints ***"Fire prevails"*** if **p** is greater than n
* Prints ***"Frozen Fire"*** if they are **equal**
[/task-description]
[code-io /]
[/code-task]
[/slide]

[slide]
# Problem: Valid Triangle
[code-task title="Valid Triangle" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
[code-io /]
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
[code-task title="Sum of Numbers" executionStrategy="python-code" requiresInput]
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
[code-io /]
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
[code-io /]
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
