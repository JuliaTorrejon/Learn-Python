## String Formatting with % - Part 2

Remember, we used the `%` operator to replace the `%s` placeholders with the variables in parentheses.

``` python
name = "Mike"
print "Hello %s" % (name)
```

You need the same number of `%s` terms in a string as the number of variables in parentheses:

``` python
print "The %s who %s %s!" % ("Knights", "say", "Ni")
# This will print "The Knights who say Ni!"
```

## Code Example

Instructions  | 
------------  | 
Now it's your turn! We have ___ in the code to show you what you need to change!
1.Inside the string, replace the three ___ with %s.
2.After the string but before the three variables, replace the final ___ with a %.
3.Hit Run.
4.Answer the questions in the console as they pop up! Type in your answer and hit Enter.

``` python
name = raw_input("What is your name? ")
quest = raw_input("What is your quest? ")
color = raw_input("What is your favorite color? ")

print "Ah, so your name is %s, your quest is %s, " \
"and your favorite color is %s." % (name, quest, color)
```
