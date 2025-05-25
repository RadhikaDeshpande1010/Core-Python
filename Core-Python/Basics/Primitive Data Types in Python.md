<html>
 <body>
  <h2><sub><img src="https://github.com/RadhikaDeshpande1010/icon-library/blob/main/python-icon/python-icon.png" height="25" width="25"></sub> Python Basics</h2>
  <h2>Primitive Data Types in Python</h2>
  <p>In Python, primitive variables refer to simple data types that hold basic values. They serve as the building blocks of programming, laying the foundation for more advanced structures like lists, dictionaries, and custom objects.</p>
  
  <p>:black_small_square:<strong>Integers (int)</strong> → Whole numbers</p>
  
  ```python
  x = 10
  ```
  <p>:black_small_square:<strong>Floating-point (float)</strong> → Numbers with decimals</p>
  
  ```python
  x = 10.5
  ```
  <p>:black_small_square:<strong>String (str)</strong> → Text enclosed in quotes</p>
  
  ```python
  text = "Python"
  ```
  <p>:black_small_square:<strong>Boolean (bool)</strong> → True or False</p>
  
  ```python
  is_active = True 
  ```

<h5>Key Properties:</h5>
<p>:black_small_square: Immutable → Primitive variables cannot be changed once created (e.g., str, int, float).</p>
<p>:black_small_square:Simple Storage → They store single values, unlike complex structures like lists or dictionaries.</p>

<h2>Variable Declaration</h2>
<p>In Python, variables are declared by assigning a value to a name, without requiring explicit type declarations. Memory is allocated to the value itself, rather than the variable name.</p>

```python
x = 10            # Integer
pi = 3.14         # Float
name = "Radhika"  # String
is_active = True  # Boolean
```
<p>The advantages of Python's variable declaration system include:</p>
<p>:black_small_square:	Ease of Use → No need for explicit type declarations, making coding faster and more intuitive.</p>
<p>:black_small_square:	Dynamic Typing → Variables automatically adjust their type based on the assigned value.</p>
<p>:black_small_square:	Memory Optimization → Memory is allocated to the value itself, reducing unnecessary space usage.</p>
<p>:black_small_square:	Flexibility → Variables can store different types of data at different points in a program.</p>
<p>:black_small_square: Concise Code → Simplifies code structure, improving readability and efficiency.</p>

<h2>Demonstration on Variable declarations</h2>
<p>Here's a demonstration of variable declarations in Python, showcasing different ways to define and use variables.</p>

<h4>1. Basic Variable Assignment</h4>
<h6>Example 1:</h6>

```python
Input
a = 10
print(a)
  
Output
10
```

```python
Input
type(a)
  
Output
int
```
<h6>Example 2:</h6>

```python
Input
text = "Python"
print(text)
  
Output
Python
```

```python
Input
type(text)
  
Output
Str
```
<h6>Example 3:</h6>

```python
x = 10            # Integer
pi = 3.14         # Float
name = "Radhika"  # String
is_active = True  # Boolean
```

```python
Input
print(num, ',', pi, ',', text, ',', b)
  
Output
10 , 3.14 , Hello world , True
```

```python
Input
type(num)
Output
int

Input
type(pi)
Output
float

Input
type(text)
Output
str

Input
type(b)
Output
bool
```

<h4>2. Multiple Assignments</h4>
<h6>Example 1:</h6>

```python
Input
a, b, c = 5, 10, 2   # Assign multiple values
print(a,b,c)
  
Output
5 10 2
```
<h6>Example 2:</h6>

```python
Input
a = b = c = 5		# Assign the same value to multiple variables
print(a,b,c)
  
Output
5
```

<h4>3. Dynamic Typing in Python</h4>
<p>Python variables are dynamically typed, meaning they can store different types of values.</p>

```python
Input
value = "Hello"
print(type(value))
value = 25
print(type(value))
  
Output
<class 'str'>
<class 'int'>
```

<h4>4. Using id() to Check Memory Allocation:</h4>
<p>In Python, the id() function returns the unique memory address of an object. When used with print(), it displays the memory location where a variable is stored.</p>
<h6>Example 1:</h6>

```python
Input
a = 15
print(id(a))
  
Output
140707080186744    #  unique memory address of an object (a)
```
<h6>Example 2:</h6>

```python
Input
x = 200
y = x
print(id(x), id(y))
  
Output
140707080192664 140707080192664    #  unique memory address of object's (x) and (y)
```

<h2>Operations on Data Primitives</h2>
<p>Operations on data primitives in Python involve basic computations and manipulations using fundamental data types.</p>
<h4>1. Numeric Types (int,float)</h4>
<p>In Python, when you add two integers, the result is also an integer.</p>
<p>int + int → int</p>

```python
Input
22 + 33     # Integer + Integer = Integer

Output
55
```
<p>When you add an integer (int) and a float, Python automatically converts the result to a float.</p>
<p>int + float → float (Automatic type conversion)</p>

```python
Input
22 + 33.0    # Integer + Float = Float

Output
55.0
```
<h4>2. String Operations (+,*)</h4>
<h4>:black_small_square: Concatenation (+)</h4>
<p>In Python, when you use the + operator with strings, it performs concatenation rather than arithmetic addition.</p>
<p>str + str → str (Joins two strings together)</p>

```python
Input
'22' + '33'   # String + String = String Concatenation

Output
2233
```
<h4>:black_small_square: Repetition (*)</h4>
<p>In Python, when you multiply a string by an integer, it creates a repeated copy of the string.</p>
<p>str * int → str (Creates multiple copies of the string)</p>

```python
Input
'22ab' * 3    # String * Integer = String Replica

Output
'22ab22ab22ab'
```
</body>
</html>
