<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/skill-icon/blob/main/general-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Operator Precedence</h2>
  <p>In Python, operator precedence determines the order in which operators are evaluated in an expression. Operators with higher precedence are evaluated first</p>
  
  | Operator               | Description                                  |
  |------------------------|----------------------------------------------|
  | `()`, `[]`, `{}`       | Parentheses (Grouping)                       |
  | `[index]`, `[i:j]`     | Subscription, Slicing                        |
  | `**`                   | Exponentiation                               |
  | `+x`, `-x`, `~x`       | Unary operators                              |
  | `*`, `/`, `//`, `%`    | Multiplication, Division, Floor Division, Modulus |
  | `+`, `-`               | Addition, Subtraction                        |
  | `<<`, `>>`             | Bitwise shift operators                      |
  | `&`                    | Bitwise AND                                  |
  | `^`                    | Bitwise XOR                                  |
  | `|`                    | Bitwise OR                                   |
  | `==`, `!=`, `>`, `<`, `>=`, `<=` | Comparison operators                 |
  | `is`, `is not`         | Identity operators                           |
  | `in`, `not in`         | Membership operators                         |
  | `not`                  | Logical NOT                                  |
  | `and`                  | Logical AND                                  |
  | `or`                   | Logical OR                                   |
  | `=`, `+=`, `-=`, `*=`, `/=`, etc. | Assignment operators                |

  <h6>Example 1:</h6>
  
  ```python
  Input
  4 + 3 * 6 ** 2 / 3
  
  Output
  40
  ```

  <h6>Step-by-Step Evaluation of Example 1:</h6>
  <p>
    
   ```
   Exponentiation (**) first:
   6 ** 2 = 36
   Expression becomes: 4 + 3 * 36 / 3
   ```
   ```
   Multiplication and Division (left to right):
   3 * 36 = 108
   108 / 3 = 36.0
   Expression becomes: 4 + 36.0
   ```
   ```
   Addition:
   4 + 36.0 = 40.0
   ```
  </p>

  <h6>Example 2:</h6>
  
  ```python
  Input
  10 + (5 * 20)
  
  Output
  110
  ```

  <h6>Step-by-Step Evaluation of Example 2:</h6>
  <p>
   
   ```
   Parentheses first (()):
   5 * 20 = 100
   ```

   ```
   Now the expression becomes:
   10 + 100 = 110
   ```
   </p>
 </body>
<html>
