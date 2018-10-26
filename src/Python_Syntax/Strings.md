## Strings

When printing things in Python, we are supplying a text block that we want to be printed. Text in Python is considered a specific type of data called a _string_. A string, so named because they're a series of letters, numbers, or symbols connected in order — as if threaded together by string. Strings can be defined in different ways:

``` python
print "This is a good string"
print 'You can use single quotes or double quotes for a string'
```

Above we printed two things that are strings and then attempted to print two things that are not strings. While double-quotes (") and single-quotes (') are both acceptable ways to define a string, a string needs to be opened and closed by the same type of quote mark.

We can combine multiple strings using `+`, like so:

``` python
print "This is " + "a good string"
```

This code will print out "This is a good string".

## Code Example

Instructions  | 
------------  |
We're trying to figure out how much it rained in the past year! Update the annual_rainfall variable to include the values from September to December.       |

```python 
january_to_june_rainfall = 1.93 + 0.71 + 3.53 + 3.41 + 3.69 + 4.50
annual_rainfall = january_to_june_rainfall

julu_rainfall = 1.05
annual_rainfall += july_rainfall

august_rainfall = 4.91
annual_rainfall = += august_rainfall

september_rainfall = 5.16
october_rainfall = 7.20
november_rainfall = 5.06
december_rainfall = 4.06
```
