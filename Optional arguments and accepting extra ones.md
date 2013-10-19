Optional Arguments
==================
Say you have a function called increment().You want it to add 1 but also add other numbers if possible.
How do you do this? Optional arguments! Like this:
```python
def increment(number,value=1):
  return number + value
```
increment(5) -> 6
increment(5,2) -> 7
increment(5,value=2) -> 7 
increment(number=5,value=2) -> 7
Value has a default value of one if the argument is not specified.
Accepting extra arguments
========================
