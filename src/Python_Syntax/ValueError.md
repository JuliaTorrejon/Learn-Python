## Value Error

Python automatically assigns a variable the appropriate datatype based on the value it is given. A variable with the value `7` is an integer, `7`. is a float, `"7"` is a string. Sometimes we will want to convert variables to different datatypes. For example, if we wanted to print out an integer as part of a string, we would want to convert that integer to a string first. We can do that using `str()`:

```python
age = 13
print "I am " + str(age) + " years old!"
````

This would print:

```python
>>> "I am 13 years old!"
````

Similarly, if we have a string like `"7"` and we want to perform arithmetic operations on it, we must convert it to a numeric datatype. 
We can do this using `int()`:

```python
number1 = "100"
number2 = "10"

string_addition = number1 + number2 
#string_addition now has a value of "10010"

int_addition = int(number1) + int(number2)
#int_addition has a value of 110
````

If you use `int()` on a floating point number, it will round the number down. To preserve the decimal, you can use `float()`:
```python
string_num = "7.5"
print int(string_num)
print float(string_num)
````

```python
>>> 7
>>> 7.5
```

