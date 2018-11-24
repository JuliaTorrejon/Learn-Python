## Access by Index

Each character in a string is assigned a number. This number is called the __index__. Check out the diagram in the editor.

``` python
c = "cats"[0]
n = "Ryan"[3]
```

1. In the above example, we create a new variable called `c` and set it to `"c"`, the character at index zero of the string `"cats"`.
2. Next, we create a new variable called `n` and set it to `"n"`, the character at index three of the string `"Ryan"`.

Notice that in the first "cat" example we are calling the 0th letter of "cat" and getting "c" in return. 
This is because in Python indices begin counting at 0. Therefore, in the string "cats", the first letter, "c", 
is at the 0th index and the last letter, "s", is at the 3rd index.

## Code Example 

Instructions  | 
------------  | 
1.Assign the variable fifth_letter equal to the fifth letter of the string "MONTY". Remember that the fifth letter is not at index 5. Start counting your indices from zero.

``` python
"""
The string "PYTHON" has six characters,
numbered 0 to 5, as shown below:

+---+---+---+---+---+---+
| P | Y | T | H | O | N |
+---+---+---+---+---+---+
  0   1   2   3   4   5

So if you wanted "Y", you could just type
"PYTHON"[1] (always start counting from 0!)
"""
fifth_letter = "MONTY"[4]

print fifth_letter
```
