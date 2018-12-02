## Conditional Statement Synatx

`if` is a conditional statement that executes some specified code after checking if its expression is `True`.

Here's an example of `if` statement syntax:

``` python
if 8 < 9:
if 8 < 9:
  print "Eight is less than nine!"
  ```
  
In this example, `8 < 9` is the checked expression and print `"Eight is less than nine!"` is the specified code.

Pay attention to the indentation before the `print` statement. This space, called white space, is how Python knows we are entering a new block of code. Python accepts many different kinds of indentation to indicate blocks. In this lesson, we use four spaces but elsewhere you might encounter two-space indentation or tabs (which Python will see as different from spaces).

If the indentation from one line to the next is different and there is no command (like `if`) that indicates an incoming block then Python will raise an `IndentationError`. These errors could mean, for example, that one line had two spaces but the next one had three. Python tries to indicate where this error happened by printing the line of code it couldn't parse and using a ^ to point to where the indentation was different from what it expected.

## Code Example

Instructions  | 
------------  | 
If you think the print statement will print to the console, set response equal to `'Y'`; otherwise, set response equal to `'N'`.

``` python
response = 'Y'

answer = "Left"
if answer == "Left":
    print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    
# Will the above print statement print to the console?
# Set response to 'Y' if you think so, and 'N' if you think not.
```

