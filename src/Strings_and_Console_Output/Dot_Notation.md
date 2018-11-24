## Dot Notation

Let's take a closer look at why you use `len(string)` and `str(object)`, but dot notation (such as `"String".upper())` for the rest.

``` python
lion = "roar"
len(lion)
lion.upper()
```
Methods that use dot notation only work with strings.

On the other hand, `len()` and `str()` can work on other data types.

## Code Example

Instructions  | 
------------  | 
1.Call the len() function with the argument ministry.
2.Invoke the ministry's .upper() function.

``` python
ministry = "The Ministry of Silly Walks"

print len(ministry)
print ministry.upper()
```
