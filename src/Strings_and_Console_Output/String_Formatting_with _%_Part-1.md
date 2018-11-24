## String Formatting with % -   Part 1

When you want to print a variable with a string, there is a better method than concatenating strings together.

``` python
name = "Mike"
print "Hello %s" % (name)
```

The `%` operator after the string is used to combine a string with variables. The `%` operator will replace the `%s` in the string 
with the string variable that comes after it.

If you'd like to print a variable that is an integer, you can "pad" it with zeros using `%02d`. The `0` means "pad with zeros", 
the 2 means to pad to `2` characters wide, and the `d` means the number is a signed integer (can be positive or negative).

``` python
day = 6
print "03 - %s - 2019" %  (day)
# 03 - 6 - 2019
print "03 - %02d - 2019" % (day)
# 03 - 06 - 2019
```

## Code Example

Instructions  | 
------------  | 
1.Take a look at the code in the editor. What do you think it'll do? Click Run when you think you know.

``` python
string_1 = "Camelot"
string_2 = "place"

print "Let's not go to %s. 'Tis a silly %s." % (string_1, string_2)
```
