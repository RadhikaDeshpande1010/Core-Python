<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/icon-library/blob/main/python-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Type Conversion</h2>
  <p>In Python, type conversion (also called type casting) refers to converting data from one data type to another. There are two types:</p>

  <h4>1. Implicit Type Conversion</h4>
  <p>Python automatically converts a data type without the programmer's intervention.</p>
    
  ```python
  Input
  a = 10		  # Int
  b = 15.0	  # Float
  c = a + b	  # Python converts 'a' into float automatically print(c)

  Output
  25.0
  ```
  <h4>2. Explicit Type Conversion</h4>
  <p>You manually convert data types using functions like int(), float(), str(), etc..</p>
  <h6>Example 1:</h6>
  
  ```python
  Input
  a = 10 # Integer
  print(str(a))     # If (a) is a variable containing a value (int), str(a) temporarily converts (a) to a string for that specific operation—it doesn't change the original type of (a)
  type(a)

  Output
  10
  int
  ```
  <h6>Example 2:</h6>
  
  ```python
  To convert (a) int value to string, you can store it in variable.

  Input
  x = str(a)       # When you write x = str(a), it permanently assigns (x) as a string version of (a). However, a itself remains unchanged
  print(x)
  type(x)

  Output
  10
  str
  ```
 <h6>Example 3:</h6>
  
  ```python
  Input
  f = '20.2'
  y = float(f)
  print(y)
  type(y)

  Output
  20.2
  float
  ```
  <h4>3. Common conversion functions</h4>
  <p>Here are some common type conversion functions in Python:</p>
  
  | Function     | Description                                                                 |
  |--------------|-----------------------------------------------------------------------------|
  | `int(x)`     | Converts `x` to an integer (if possible)                                    |
  | `float(x)`   | Converts `x` to a floating-point number                                     |
  | `str(x)`     | Converts `x` to a string                                                    |
  | `list(x)`    | Converts `x` to a list                                                      |
  | `tuple(x)`   | Converts `x` to a tuple                                                     |
  | `set(x)`     | Converts `x` to a set                                                       |
  | `dict(x)`    | Converts `x` to a dictionary (if `x` is a valid key-value sequence)         |
  | `bool(x)`    | Converts `x` to a boolean (`True` or `False`)                               |
  
  <h4>4. Common Conversion Types</h4>
  <p>In Python, you can convert between different data types. Here’s a quick guide:</p>
  <h5>Python Type Conversion Mapping:</h5>

  | From               | To                  |
  |--------------------|---------------------|
  | `int` (Integer)     | `float` (Decimal)   |
  | `int` (Integer)     | `str` (String)      |
  | `float` (Decimal)   | `int` (Integer)     |
  | `float` (Decimal)   | `str` (String)      |
  | `str` (String)      | `int` (Integer)     |
  | `str` (String)      | `float` (Decimal)   |
  | `str` (String)      | `list` (List)       |
  | `list` (List)       | `str` (String)      |
  | `list` (List)       | `tuple` (Tuple)     |
  | `list` (List)       | `set` (Set)         |
  | `tuple` (Tuple)     | `list` (List)       |
  | `set` (Set)         | `list` (List)       |
  | `dict` (Dictionary) | `list` (Keys only)  |
  | `bool` (Boolean)    | `int` (Integer)     |
  | `bool` (Boolean)    | `str` (String)      |
