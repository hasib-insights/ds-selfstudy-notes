<b>Variables</b>
```python
variavle_name = value
```
<b>Basic variable declaration</b>
```python
x = 5
y = "hasib"
print(x)
print(y)
```
output:
```
5
Hasib
```
<b>print this variable</b>
```python
x = 4       # x is of type int
x = "Hasib" # x is now of type str
print(x)
```
output: 
```
Hasib
```
<b>Casting</b>
```python
x = str(3)    # string 
y = int(3)    # integer
z = float(3)  # floating
```
output:
```
'3'
3
3.0
```
<b>Get the Type</b>    
get the data type of a variable with the type() function.
```python
x = 5
y = "John"
print(type(x))
print(type(y))
```
output:
```
<class 'int'>
<class 'str'>
```
String variables can be declared either by using single or double quotes:
```python
x = "John"
# is the same as
x = 'John'
```
## Legal variable names

-A variable name must start with a letter or the underscore character  
-A variable name cannot start with a number  
-A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )  
-Variable names are case-sensitive (age, Age and AGE are three different variables)  
-A variable name cannot be any of the Python keywords.

Example
```python
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
```
<b>Illegal variable names</b>
```python
2myvar = "John"
my-var = "John"
my var = "John"

``` 

