## Compare Closely

Let's start with the simplest aspect of control flow: __comparators__. There are six:

__Equal to `(==)`__

```pyhton
>>> 2 == 2
True
>>> 2 == 5
False
```

__Not Equal to `(!=)`__

```python
>>> 2 != 5
True
>>> 2 != 2
False
```

__Less than (<)__

```python
>>> 2 < 5
True
>>> 5 < 2
False
```

__Less than or equal to (<=)__

```python
>>> 2 <= 2
True
>>> 5 <= 2
False
```

__Greater than (>)__

```python
>>> 5 > 2
True
>>> 2 > 5
False
```

__Greater than or equal to (>=)__

```python
>>> 5 >= 5
True
>>> 2 >= 5
False
```

Comparators check if a value is (or is not) equal to, greater than (or equal to), or less than (or equal to) another value.

Note that == compares whether two things are equal, and = assigns a value to a variable.

## Code Example

Instructions  | 
------------  | 
Set each variable to `True` or `False` depending on what you think the result will be. For example, `1 < 2` will be `True`, because one is less than two.
1.Set `bool_one` equal to the result of `17 < 328`
2.Set `bool_two` equal to the result of `100 == (2 * 50)`
3.Set `bool_three` equal to the result of `19 <= 19`
4.Set `bool_four` equal to the result of `-22 >= -18`
5.Set `bool_five` equal to the result of `99 != (98 + 1)``

```python
# Assign True or False as appropriate on the lines below!

# Set this to True if 17 < 328 or to False if it is not.
bool_one = True   # We did this one for you!

# Set this to True if 100 == (2 * 50) or to False otherwise.
bool_two = True

# Set this to True if 19 <= 19 or to False if it is not.
bool_three = True

# Set this to True if -22 >= -18 or to False if it is not.
bool_four = False

# Set this to True if 99 != (98 + 1) or to False otherwise.
bool_five = False
