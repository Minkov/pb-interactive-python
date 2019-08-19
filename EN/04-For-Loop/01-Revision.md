[slide]
# Revision 
Before proceeding ahead, let's remind ourselves about the program concepts and techniques that we have learned in the last session.

## Nested Conditions
Pretty often the program logic requires the use of `if` or `if-else` statements, which are contained one inside another. 

They are called **nested** `if` or `if-else` statements. 

As implied by the title **"nested"**, these are `if` or `if-else` statements that are placed inside other `if` or `else` statements.
```py
if condition1:
  if condition2:
    // body; 
  else:
    // body
```

## Complex Conditions with AND, OR, NOT and ()
```py
if (x == left or x == right) and y >= top and y <= bottom):
  print(…)
```

### Logical AND

The logical **"AND"** (operator `and)` means a few conditions have to be **fulfilled simultaneously**. 

The following table of truthfulness is applicable:

| a | b  | a and b |
|---|---|---|
| True | True | True |
| True | False | False |
| False | True | False |
| False | false | False |

### Logical OR
The logical **"OR"** (operator `||`) means that **at least one** among a few conditions is fulfilled. Similar to the operator `&&,` the logical **"OR"** accepts a few arguments of **bool** (conditional) type and returns `true` or `false`.

| a | b  | `a or b` |
|---|---|---|
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |

### Logical Negation (NOT)
**Logical negation** (operator `not`) means a given condition is **not fulfilled**.

| a | not a |
|---|---|
| True | False |

The operator `not` accepts as an **argument** a bool variable and **returns** its value.
[/slide]

[slide]
# Video

[vimeo-video videoId="342410322" startTimeInSeconds="996" endTimeInSeconds="1252" /]

[/slide]