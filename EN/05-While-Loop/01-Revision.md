[slide]
# Revision

## For Loop
A `for` loop is used for iterating over a sequence (string is a sequence for example). With the `for` loop we can execute a set of statements multiple times.

```python
for char in "banana":
  print(char)
```

## The range() Function
The `range()` function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), and ends at a specified number:
```python
for x in range(5):
  print(x)
```

The `range()` function defaults to 0 as a starting value, however it is possible to specify the starting value by adding a parameter: `range(1, 5)`, which means values from 1 to 5 (but not including 5):
```python
for x in range(1, 5):
  print(x)
```

The `range()` function defaults to increment the sequence by 1, however it is possible to specify the increment value by adding a third parameter: `range(1, 15, 2)`:
```python
for x in range(1, 15, 2):
  print(x)
```
[/slide]

[slide]
# Video

[vimeo-video videoId="343587107" startTimeInSeconds="1025" endTimeInSeconds="1220" /]

[/slide]