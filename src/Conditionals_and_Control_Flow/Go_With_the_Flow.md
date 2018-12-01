## Go With the Flow
Just like in real life, sometimes we'd like our code to be able to make decisions.

The Python programs we've written so far have had one-track minds: they can add two numbers or `print` something, but they don't have the 
ability to pick one of these outcomes over the other.

__Control flow__ gives us this ability to choose among outcomes based on what else is happening in the program.

## Code Example

Instructions  | 
------------  | 
Check out the code in the editor. You'll see the type of program you'll be able to write once you've mastered control flow. Click Run to see what happens!

```python
def clinic():
    print "You've just entered the clinic!"
    print "Do you take the door on the left or the right?"
    answer = raw_input("Type left or right and hit 'Enter'.").lower()
    if answer == "left" or answer == "l":
        print "This is the Verbal Abuse Room, you heap of parrot droppings!"
    elif answer == "right" or answer == "r":
        print "Of course this is the Argument Room, I've told you that already!"
    else:
        print "You didn't pick left or right! Try again."
        clinic()
clinic()```
