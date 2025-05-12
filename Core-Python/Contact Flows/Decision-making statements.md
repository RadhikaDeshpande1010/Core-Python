<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/skill-icon/blob/main/general-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Conditional Statements</h2>
   
  -	In Python, conditional statements allow the program to make decisions based on conditions.
  -	In Python, conditional statements use relational operators to compare values, and based on the result (True or False), they execute different parts of the code.
  -	Relational operators help in validating conditions(expressions) before running the logic.
  -	The most common conditional statements are:

  <h2>If Statement</h2>
  <p>The if condition in Python allows your program to make decisions based on a given condition. The code inside the if block runs only if the condition is True.</p>
  <h5>If Statement Syntax</h5>

  ```python
  if condition:
      # Code to execute if condition is True
  Note: Here, four spaces (Indentation) indicates that sequence of statements you mention fall under the if block.
  ```
  <h6>Example 1:</h6>

  ```python
  if 2 < 3:
    print("true")

  Output
  true
  ```
  <h6>Example 2:</h6>

  ```python
  if 2 == 2:
      print("Hello")
  print("End of the program")

  Output
  Hello
  End of the program
  ```
  <h6>Example 3:</h6>

  ```python
  if 2 > 3:
      print("Hello")
  print("End of the program")

  Output
  End of the program
  ```
  <h6>Example 4:</h6>

  ```python
  if True:
      print("Hello")
  print("End of the program")

  Output
  Hello
  End of the program
  ```
  <h6>Example 5:</h6>

  ```python
  if False:
      print("Hello")
  print("End of the program")

  Output
  End of the program
  ```

  <h2>If-Else Statement</h2>
  <p>The if-else statement in Python allows a program to make decisions based on conditions. If a condition is True, it runs one block of code; if it's False, it runs another.</p>
  <h5>How It Works:</h5>
  
  - The program checks the condition inside if.
  -	If it's True, the code under if runs.
  -	If it's False, the code under else runs.

  <h5>If-Else Statement Syntax</h5>

  ```python
  if condition:
      # Code to execute if condition is True
  else:
      # Code to execute if condition is False
  ```
  <h6>Example 1:</h6>

  ```python
  if 2 < 3:
      print("true")
  else:
      print("false")

  Output
  true
  ```
  <h6>Example 2:</h6>

  ```python
  if False:
      print("Hello")
  else:
      print("Bye")
  print("End of the program")

  Output
  Bye
  End of the program
  ```
  <h6>Example 3:</h6>

  ```python
  if True:
      print("Hello")
  else:
      print("Bye")
  print("End of the program")

  Output
  Hello
  End of the program
  ```
  <h6>Example 4:</h6>

  ```python
  if 2 == 2:
      print("Hello")
  else:
      print("Bye")
  print("End of the program")

  Output
  Hello
  End of the program
  ```

  <h2>If-Elif-Else Statement</h2>
 
  - The if-elif-else statement in Python is used when multiple conditions need to be checked one after another.
  - It helps control flow by testing conditions sequentially.

  <h5>If-Elif-Else Statement Syntax</h5>

  ```python
  if condition1:
      # Code executes if condition1 is True
  elif condition2:
      # Code executes if condition1 is False but condition2 is True
  else:
      # Code executes if none of the conditions are True
  ```
  <h6>Example 1:</h6>

  ```python
  name = input("Enter the name: ")
  age = int(input("Enter the age: "))
  
  if age <= 20:
      print("Individual is Student")
  elif age <= 30:
      print("Individual is Employee")
  elif age <= 40:
      print("Individual is Employee and Married")
  elif age <= 50:
      print("Individual is Experienced Professional")
  elif age <= 60:
      print("Individual is a Senior Professional")
  else:
      print("Individual is Senior Citizen")

  User Input
  Enter the name:  Sam
  Enter the age:  53
  
  Output
  Individual is a Senior Professional
  ```
</body>
</html>
