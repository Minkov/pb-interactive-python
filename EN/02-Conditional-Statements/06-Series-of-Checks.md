[slide]
# Sequence of If-Else Conditions
Sometimes we need to do a sequence of conditions before we decide what actions our program will execute

In such cases, we can apply the construction if-else if ... -else in series

For this purpose, we use the following format:
```python
if ... : 
  # Execution code
elif ... : 
  # Execution code
elif ... :
  # Execution code
```

# Example
The program checks the first condition, finds that it is true and ends
```python
a = 7
if a > 4:
  print("Bigger than 4") 
elif a > 5:
  print("Bigger than 5") 
else 
  print("Equal to 7") 
```

The result of this program will be **`"Bigger than 4"`**
[/slide]

[slide]
# Problem: Number 1...9
[code-task title="Number 1...9" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **integer** and checks its value \[1, 9\]
* Prints the value in the form of text
* If the number is **greater** than 9 prints ***"Number too big"***
[/task-description]
[tests]
[test]
[input]
5
[/input]
[output]
five
[/output]
[/test]
[test]
[input]
3
[/input]
[output]
three
[/output]
[/test]
[test]
[input]
18
[/input]
[output]
Number too big
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
Number too big
[/output]
[/test]
[test]
[input]
4
[/input]
[output]
four
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|7|even|
|10|Number too big|
[/slide]

[slide]
# Solution: Number 1...9
[code-task title="Number 1...9" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
num = int(input())
if num == 1:
  print("one")
elif num == 2:
  print("two")
elif num == 3:
  print("three")
elif num == 4:
  print("four")
elif num == 5:
  print("five")
elif num == 6:
  print("six")
elif num == 7:
  print("seven")
elif num == 8:
  print("eight")
elif num == 9:
  print("nine")
else:
  print("Number too big")
```
[/code-editor]
[task-description]
Write a program, which:

* Reads an **integer** and checks its value \[1, 9\]
* Prints the value in the form of text
* If the number is **greater** than 9 prints ***"Number too big"***
[/task-description]
[tests]
[test]
[input]
5
[/input]
[output]
five
[/output]
[/test]
[test]
[input]
3
[/input]
[output]
three
[/output]
[/test]
[test]
[input]
18
[/input]
[output]
Number too big
[/output]
[/test]
[test]
[input]
10
[/input]
[output]
Number too big
[/output]
[/test]
[test]
[input]
4
[/input]
[output]
four
[/output]
[/test]
[/tests]
[/code-task]
# Sample Input and Output
|Input|Output|
|-----|------|
|7|even|
|10|Number too big|
[/slide]

[slide]
# Video

[vimeo-video videoId="341553633" startTimeInSeconds="3225" endTimeInSeconds="4025" /]

[/slide]