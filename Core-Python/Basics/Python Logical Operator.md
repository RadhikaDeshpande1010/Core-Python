<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/skill-icon/blob/main/general-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Logical Operators</h2>
  <p>In python, logical operators help make decisions in programming by combining conditions statements. They help in decision-making by evaluating expressions and returning a True or False result.</p>

  <h4>:black_small_square: AND</h4>
  <p>Returns True if both the operands are true</p>
  
  | Input A | Input B | Output (A AND B) |
  |---------|---------|------------------|
  | True    | True    | True             |
  | False   | True    | False            |
  | True    | False   | False            |
  | False   | False   | False            |


  ```python
  Input
  5 < 3 and 5 > 2
  
  Output
  False
  ```
   
  ```python
  Input
  10 < 11 and 10 > 9
  
  Output
  True
  ```
  <h4>:black_small_square: OR</h4>
  <p>Returns True if either of the operands is true</p>

  | Input A | Input B | Output (A OR B) |
  |---------|---------|-----------------|
  | True    | True    | True            |
  | False   | True    | True            |
  | True    | False   | True            |
  | False   | False   | False           |

  ```python
  Input
  10 > 5 or 5 > 9
  
  Output
  True
  ```
   ```python
  Input
  15 > 20 or 20 > 25
  
  Output
  False
  ```
  <h4>:black_small_square: NOT</h4>
  <p>Flips True to False and vice versa</p>

  | Input | Output (NOT Input) |
  |-------|---------------------|
  | True  | False               |
  | False | True                |

  ```python
  Input
  a = True
  b = False
  print(not a)
  print(not b)

  Output
  False
  True
  ```
