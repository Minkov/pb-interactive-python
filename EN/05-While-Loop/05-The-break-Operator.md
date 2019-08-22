[slide]
# The break Operator
The `break` operator stops the execution of a loop at the time it is called and continues from the first line after the end of the loop.

This means that the current iteration of the loop will not be completed, accordingly, the rest of the code in the body of the loop will not be executed.

Example: Exit the loop when i is 3:
```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1 
```
[/slide]