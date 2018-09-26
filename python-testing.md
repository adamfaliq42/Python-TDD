We use the following techniques to test and debug a Python application.

1. Assert

Assert means to say that something is certainly true. In Python we use the `assert` keyword.

For example:
```python
def add(x, y):
    return x + y
    
assert add(1, 2) == 3
```

If the function pass the `assert` test, the program will continue. If the `assert` is wrong, the program will 
return AssertionError.


2. Logging

We use logging when we want to print to the console, but we do not want the users to see the logged text. 
There are many levels of logging. For example:

- DEBUG: Detailed information used to debug your program

- INFO: Confirmation that things are working as expected

- WARNING: Something unexpected happen, but the program is still running

- ERROR: The program has not been able to perform particular function

- CRITICAL: A serious error. The program may stop running

3. Stepping 

See: `pdb` tutorial
