## Review

Great! So far we’ve looked at:

* Print statements
* How to create, modify, and use variables
* Arithmetic operations like addition, subtraction, division, and multiplication
* How to use comments to make your code easy to understand
* Different data types, including strings, ints, floats, and booleans
* Converting between data types

You can add to a variable by using +=:

```python
total += number_to_add
```

which is shorthand for:

```python
[new value of] total = [old value of] total + number_to_add
```

Instructions  | 
------------  |
1.Let's apply all of the concepts you have learned one more time! Create a variable called `skill_completed` and set it equal to the string `"Python Syntax"`.
2.Create a variable called `exercises_completed` and set it equal to `13`. Create another variable called `points_per_exercise` and set it equal to `5`.
3.Create a variable called `point_total` and set it equal to `100`.
4.Update `point_total` to be what it was before plus the result of multiplying `exercises_completed` and `points_per_exercise`.
5.Add a comment above your declaration of points_per_exercise that says: The amount of points for each exercise may change, because points don't exist yet
6.Print a string to the console that says: I got X points! with the value of `point_total` where X is.

```python
# The amount of points for each exercise may change, because points don't exist yet

skill_completed = "Python Syntax"

exercises_completed = 13
points_per_exercise = 5

point_total = 100
point_total += (exercises_completed * points_per_exercise)

print("I got " + str(point_total) + " points!")
```
