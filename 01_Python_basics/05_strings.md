## Strings
Strings in python are surrounded by either single quotation marks(''), or double quotation marks("").  
Examle
```
'hello'
"hello"
"It's alright"
```
Display a string literal with the **print()** function:
```python
print("Hello")
print('Hello')
print("It's alright")
```
out:
```
Hello
Hello
It's alright
```
## Multiline Strings
```python
a = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print(a)
```
out:
```
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
```
## Modify Strings
### Upper Case
The **upper()** method returns the string in upper case:
```python
a = "Hello, World!"
print(a.upper())
```
out:
```
HELLO, WORLD!
```
#### Lower Case
The lower() method returns the string in lower case:
```python
a = "Hello, World!"
print(a.lower())
```
out:
```
hello, world!
```
## Replace String
The **replace()** method replaces a string with another string:
```python
a = "Hello, World!"
print(a.replace("H", "J")) #(Old, new)
```
out:
```
Jello, World!
```
```python
a = "Hello, World!"
print(a.replace("0", "d", 2)) #(Old, new, count)
```
out:
```
Helld, Wdrld!
```


