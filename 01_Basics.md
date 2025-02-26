```python
# this is the first comment
spam = 1  # and this is the second comment
          # ... and now a third!
text = "# This is not a comment because it's inside quotes."
```

# Numbers

```python
>>>2 + 2
4
>>>50 - 5*6
20
>>>(50 - 5*6) / 4
5.0
>>>8 / 5  # division always returns a floating-point number
1.6
>>>17 / 3  # classic division returns a float
5.666666666666667
>>>17 // 3  # floor division discards the fractional part
5
>>>17 % 3  # the % operator returns the remainder of the division
2
>>>5 * 3 + 2  # floored quotient * divisor + remainder
17
>>>5 ** 2  # 5 squared
25
>>>2 ** 7  # 2 to the power of 7
128
```

```python
>>>width = 20
>>>height = 5 * 9
>>>width * height
900
```

```python
>>>n  # try to access an undefined variable
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'n' is not defined
```

```python
4 * 3.75 - 1
14.0
```

```python
>>>#In interactive mode, the last printed expression is assigned to the variable _. This means that when you are using Python as a desk calculator, it is somewhat easier to continue calculations
>>>tax = 12.5 / 100
>>>price = 100.50
>>>price * tax
12.5625
>>>price + _
113.0625
>>>round(_, 2)
113.06
```

# Strings

```python
>>>'spam eggs'  # single quotes
'spam eggs'
>>>"Paris rabbit got your back :)! Yay!"  # double quotes
'Paris rabbit got your back :)! Yay!'
>>>'1975'  # digits and numerals enclosed in quotes are also strings
'1975'
```

```python
>>>'doesn\'t'  # use \' to escape the single quote...
"doesn't"
>>>"doesn't"  # ...or use double quotes instead
"doesn't"
>>>'"Yes," they said.'
'"Yes," they said.'
>>>"\"Yes,\" they said."
'"Yes," they said.'
>>>'"Isn\'t," they said.'
'"Isn\'t," they said.'
```

```python
>>>s = 'First line.\nSecond line.'  # \n means newline
>>>s  # without print(), special characters are included in the string
'First line.\nSecond line.'
>>>print(s)  # with print(), special characters are interpreted, so \n produces new line
First line.
Second line.
```

```python
>>>print('C:\some\name')  # here \n means newline!
C:\some
ame
>>>print(r'C:\some\name')  # note the r before the quote
C:\some\name
```

```python
>>>print("""\
Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
""")
Usage: thingy [OPTIONS]
     -h                        Display this usage message
     -H hostname               Hostname to connect to
```

```python
>>># 3 times 'un', followed by 'ium'
>>>3 * 'un' + 'ium'
'unununium'
```

```python
>>>'Py' 'thon'
'Python'
```

```python
>>>text = ('Put several strings within parentheses '
...        'to have them joined together.')
>>>text
'Put several strings within parentheses to have them joined together.'
```

```python
#This only works with two literals though, not with variables or expressions:
>>>prefix = 'Py'
>>>prefix 'thon'  # can't concatenate a variable and a string literal
  File "<stdin>", line 1
    prefix 'thon'
           ^^^^^^
SyntaxError: invalid syntax
>>>('un' * 3) 'ium'
  File "<stdin>", line 1
    ('un' * 3) 'ium'
               ^^^^^
SyntaxError: invalid syntax
```

```python
#Concatenation
>>>prefix + 'thon'
'Python'
```

# String indexing

```python
>>>word = 'Python'
>>>word[0]  # character in position 0
'P'
>>>word[5]  # character in position 5
'n'
```

```python
>>>word = 'Python'
>>>word[0]  # character in position 0
'P'
>>>word[5]  # character in position 5
'n'
>>>word[0:2]  # characters from position 0 (included) to 2 (excluded)
'Py'
>>>word[2:5]  # characters from position 2 (included) to 5 (excluded)
'tho'
>>>word[:2]   # character from the beginning to position 2 (excluded)
'Py'
>>>word[4:]   # characters from position 4 (included) to the end
'on'
>>>word[-2:]  # characters from the second-last (included) to the end
'on'
# s[:i] + s[i:] is always equal to s
>>>word[:2] + word[2:]
'Python'
>>>word[:4] + word[4:]
'Python'
```

```python
+---+---+---+---+---+---+
 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
-6  -5  -4  -3  -2  -1
```







