## String Methods

Let's see how we can change them using __string methods__.

__String methods__ let you perform specific tasks for strings.

We'll focus on four string methods:

1. `len()`
2. `lower()`
3. `upper()`
4. `str()`

### Len()

Let's start with __len()__, which gets the length (the number of characters) of a string!

## Code Example

Instructions  | 
------------  | 
1.On line 1, create a variable named `parrot` and set it to the string `"Norwegian Blue"`.
2.On line 2, type `len(parrot)` after the word `print`, like so: `print len(parrot)`. The output will be the number of characters in `"Norwegian Blue"!`

``` python
parrot = "Norwegian Blue"
print len(parrot)
```

### Low()

You can use the `lower()` method to get rid of all the capitalization in your strings. You call `lower()` like so:

``` python
"Ryan".lower()
```

which will return `"ryan"`.

## Code Example

Instructions  | 
------------  | 
1.Call `lower()` on `parrot` (after `print`).

``` python
parrot = "Norwegian Blue"
print parrot.lower()
```

### Upper()

A similar method exists to make a string completely upper case

## Code Example

Instructions  | 
------------  | 
1.Call `upper()` on `parrot` (after `print`) in order to capitalize all the characters in the string!

``` python
parrot = "Norwegian Blue"
print parrot.upper()
```

### Str()

Now let's look at `str()`, which is a little less straightforward. 
The `str()` method turns non-strings into strings! For example:

``` python
str(2)
```
would turn 2 into "2".

## Code Example

Instructions  | 
------------  | 
1.Create a variable `pi` and set it to `3.14`. Call `str(pi)` after `print`.

``` python
pi = 3.14
print str(pi)
```
