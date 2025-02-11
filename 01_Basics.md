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







