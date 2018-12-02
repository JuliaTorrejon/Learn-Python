## If You're Having

Let's get some practice with `if` statements. Remember, the syntax looks like this:

```python
if some_function():
  # block line one
  # block line two
  # et cetera
```

Looking at the example above, in the event that `some_function()` returns `True`, then the indented block of code after it will be executed. In the event that it returns `False`, then the indented block will be skipped.

Also, make sure you notice the colons at the end of the `if` statement. We've added them for you, but they're important.

## Code Example

Instructions  | 
------------  | 
In the editor you'll see two functions. Don't worry about anything unfamiliar. We'll explain soon enough.
1.Replace the underline on line 2 with an expression that returns `True`.
2.Replace the underline on line 6 with an expression that returns `True`.
3.If you do it successfully, then both `"Success #1"` and `"Success #2"` are printed.

``` python
def using_control_once():
    if 2<3:
        return "Success #1"

def using_control_again():
    if 3>1:
        return "Success #2"

print using_control_once()
print using_control_again()
``` 
