<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/icon-library/blob/main/python-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Basic Built-In Functions</h2>
  <p>Python comes with many built-in functions that help you perform common tasks without writing extra code. Here are some important ones:</p>
  
  <h4>:black_small_square: print() function</h4>
  <p>The print() function is used to display output on the screen.</p>
  
  ```python
  Input
  print("Core Python Programming")
  
  Output
  Core Python Programming
  ```

  <h4>:black_small_square: input() function</h4>
  <p>The input() function is used to take user input from the keyboard. It always accepts input as a string and always returns output as a string</p>

  <h6>Example 1:</h6>
  
  ```python
  Input
  input()  

  User Input
  12

  Output
  '12'
  ```

  <h6>Example 2:</h6> 
  
  ```python
  Input
  input("Please enter the name: ")

  User Input
  Radhika

  Output
  'Radhika'
  ```

  <h6>Example 3:</h6> 
  
  ```python
  Input
  name = input("Enter the name: ")
  age = input("Enter the age: ")
  print(name, age)
  print("Name is: ",name,"\n" "Age is: ",age)

  User Input
  Enter the name:  Radhika
  Enter the age:  27
  
  Output
  Radhika 27
  Name is:  Radhika 
  Age is:  27
  ```

  <h6>Example 4:</h6> 
  
  ```python
  Input
  name = input("Enter the name: ")
  age = int(input("Enter the age: "))
  print("Name is: ",name,"\n" "Age is: ",age)
  age = age + 10
  print("Name is: ",name,"\n" "Age is: ",age)

  User Input
  Enter the name:  Radhika
  Enter the age:  27
  
  Output
  Name is:  Radhika 
  Age is:  27
  Name is:  Radhika 
  Age is:  37
  ```

 <h4>:black_small_square: f-string</h4>
 <p>An f-string in Python helps you put variables and expressions inside a string easily. You just add f before the string and use {} to include values.</p>

 ```python
  Input
  name = input("Enter the name: ")
  age = input("Enter the age: ")
  print(f'name is: {name} and age is: {age}')

  User Input
  Enter the name:  Radhika
  Enter the age:  27
  
  Output
  name is: Radhika and age is: 27
  ```

 <h4>:black_small_square: type() function</h4>
 <p>In Python, the type() function returns the data type of an object. If a is a variable, type(a) will tell you its type.</p>
 
  ```python
  Input
  a = 10
  type(a)
  
  Output
  int
  ```
</body>
<html>
