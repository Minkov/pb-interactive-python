[slide]
# For Loop
In programming it is often required to perform a block of commands multiple times. 

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

```py
for i in iterable:
  print(i)
```

Iterable means collection that can be iterated over. Example for that are strings.

Let's examine an example of a `for` loop that passes sequentially through the letters in the word `"banana"`:
```py
for letter in "banana":
  print(letter)
```
[/slide]

[slide]
# Problem: Characters
[code-task title="Characters" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```

[/code-editor]
[task-description]
Write a program, which:

- Receives a single string
- Print each character of that string on a new line

[/task-description]
[tests]
[test]
[input]
ball
[/input]
[output]
b
a
l
l
[/output]
[/test]
[/tests]
[/code-task]

# Sample Input and Output

| Input | Output |
| ----- | ------ |
| Hello | H      |
|       | e      |
|       | l      |
|       | l      |
|       | o      |

[/slide]

[slide]

# Solution: Characters

[code-task title="Characters" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]

```
text = input()
for char in text:
  print(char)
```

[/code-editor]
[task-description]
Write a program, which:

- Receives a single string
- Print each character of that string on a new line

[/task-description]
[tests]
[test]
[input]
ball
[/input]
[output]
b
a
l
l
[/output]
[/test]
[/tests]
[/code-task]

# Sample Input and Output

| Input | Output |
| ----- | ------ |
| Hello | H      |
|       | e      |
|       | l      |
|       | l      |
|       | o      |

[/slide]

[slide]
# Video

[vimeo-video videoId="342410322" startTimeInSeconds="1330" endTimeInSeconds="1655" /]

[/slide]