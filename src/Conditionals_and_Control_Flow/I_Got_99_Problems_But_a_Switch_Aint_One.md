## I Got 99 Problems, But a Swicth Ain't One

`elif` is short for "else if." It means exactly what it sounds like: "otherwise, if the following expression is true, do this!"

```python
if 8 > 9:
  print "I don't get printed!"
elif 8 < 9:
  print "I get printed!"
else:
  print "I also don't get printed!"
 ``` 
  
In the example above, the `elif` statement is only checked if the original `if` statement is `False`.

```python
def greater_less_equal_5(answer):
    if answer>5:
        return 1
    elif answer<5:          
        return -1
    else:
        return 0
        
print greater_less_equal_5(4)
print greater_less_equal_5(5)
print greater_less_equal_5(6)
``` 
