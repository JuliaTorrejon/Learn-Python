## This and That or This But Not That

Boolean operators aren't just evaluated from left to right. Just like with arithmetic operators, there's an order of operations for boolean operators:

1. `not` is evaluated first;
2. `and` is evaluated next;
3. `or` is evaluated last.

For example, `True or not False and False` returns `True`. If this isn't clear, look at the Hint.

Parentheses `()` ensure your expressions are evaluated in the order you want. Anything in parentheses is evaluated as its own unit.

## Code Example

Instructions  | 
------------  | 
Assign True or False as appropriate for `bool_one` through `bool_five`.
1.Set `bool_one` equal to the result of `False or not True and True`
2.Set `bool_two` equal to the result of `False and not True or True`
3.Set `bool_three` equal to the result of `True and not (False or False)`
4.Set `bool_four` equal to the result of `not not True or False and not True`
5.Set `bool_five` equal to the result of `False or not (True and True) False or not True and True`

``` python
bool_one = False or not True and True

bool_two = False and not True or True

bool_three = True and not (False or False)

bool_four = not not True or False and not True

bool_five = False or not (True and True)
``` 
