[slide]
# Problem: Fuel Tank
[code-task title="Fuel Tank" executionType="tests-execution" executionStrategy="python-code" requiresInput]
[code-editor language=python]
```
# Write your code here
```
[/code-editor]
[task-description]
# Description

Write a program that knows whether the tank of a vehicle needs refueling or not. 

# Input

The input is consists of 2 lines:

- First you have to read from the console the type of fuel - text with options: "diesel", "gasoline" or "gas"

- The second line of input reads the liters fuel in the tank

# Output

If the liters fuel are more than or equal to 25 print:
- "You have enough \{type of fuel\}."

Otherwise print:
- "Fill your tank with \{fuel type\}!". 

If a fuel other than the specified is introduced, "Invalid fuel!" shall be printed.

# Example

| **Input** | | **Output** |
| --- | --- | --- |
| diesel | | Fill your tank with diesel! |
| 10 | | |

| **Input** | | **Output** |
| --- | --- | --- |
| gas | | You have enough gas. |
| 25 | | |

[/task-description]
[tests]
[test]
[input]
diesel
10
[/input]
[output]
Fill your tank with diesel!
[/output]
[/test]
[test]
[input]
gasoline
40
[/input]
[output]
You have enough gasoline.
[/output]
[/test]
[test]
[input]
gas
25
[/input]
[output]
You have enough gas.
[/output]
[/test]
[test]
[input]
kerosene
200
[/input]
[output]
Invalid fuel!
[/output]
[/test]
[test]
[input]
diesel
25
[/input]
[output]
You have enough diesel.
[/output]
[/test]
[test]
[input]
gasoline
28
[/input]
[output]
You have enough gasoline.
[/output]
[/test]
[test]
[input]
gas
20
[/input]
[output]
Fill your tank with gas!
[/output]
[/test]
[test]
[input]
kerosene
20
[/input]
[output]
Invalid fuel!
[/output]
[/test]
[/tests]
[code-io /]
[/code-task]
[/slide]