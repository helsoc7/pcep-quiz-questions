# Question 1
How is a function defined in Python?
- [ ] `function my_function():`
- [x] `def my_function():`
- [ ] `new function my_function():`
- [ ] `create my_function():`

# Question 2
What is a "docstring" in Python?
- [ ] A comment that begins with `//`
- [ ] A special import statement for documentation
- [x] A documentation string at the beginning of a function, enclosed in triple quotes
- [ ] An external documentation file

# Question 3
What is the difference between a parameter and an argument in Python?
- [ ] There is no difference, both terms describe the same thing
- [x] Parameters are variables in the function definition, arguments are the values passed to the function
- [ ] Parameters are the values passed to the function, arguments are variables in the function definition
- [ ] Parameters are for simple data types, arguments are for complex data types

# Question 4
What is the output of the following code?
```python
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"

print(greet("Max"))
```
- [ ] Max, Hello!
- [x] Hello, Max!
- [ ] greeting, name!
- [ ] An error is raised

# Question 5
Which statement about return values in Python functions is correct?
- [ ] Every function must return exactly one value
- [ ] A function can return a maximum of three values
- [x] If no `return` statement is present, the function returns `None`
- [ ] The `return` statement can only appear at the end of a function

# Question 6
What is the return value of the following function when called with `my_function(5)`?
```python
def my_function(x):
    if x > 10:
        return "A"
    elif x > 5:
        return "B"
    else:
        return "C"
```
- [ ] "A"
- [ ] "B"
- [x] "C"
- [ ] None

# Question 7
How can you return multiple values from a function?
- [ ] With multiple `return` statements in sequence
- [x] By comma-separated values in a `return` statement, which returns a tuple
- [ ] By using the `multiple` keyword
- [ ] By using a global list

# Question 8
What is the output of the following code?
```python
def get_values():
    return 1, 2, 3

a, b, c = get_values()
print(b)
```
- [ ] 1
- [x] 2
- [ ] 3
- [ ] An error is raised

# Question 9
What are keyword arguments in Python?
- [ ] Arguments that only accept certain keywords as values
- [x] Arguments that are passed with the parameter name during a function call
- [ ] Arguments that are passed as dictionaries
- [ ] Arguments that are required for the function

# Question 10
Which function call is valid when the function is defined as follows?
```python
def calculate(a, b, operation="add"):
    # Function content here
```
- [ ] `calculate()`
- [ ] `calculate(operation="multiply")`
- [x] `calculate(5, 3, operation="multiply")`
- [ ] `calculate(a=5, 3, operation="multiply")`

# Question 11
What is referred to as a default parameter in the following function definition?
```python
def greet(name, message="Hello", language="en"):
    # Function content here
```
- [ ] `name`
- [ ] `message` and `name`
- [x] `message` and `language`
- [ ] All three parameters are default parameters

# Question 12
What happens when a default parameter is defined as a mutable object (e.g., a list)?
- [ ] The function generates an error, as default parameters must always be immutable
- [x] The object is created when the function is first called and reused in subsequent calls
- [ ] A new object is created with each function call
- [ ] This syntax is not allowed in Python

# Question 13
What is the scope of a variable defined inside a function?
- [x] Local to the function, not accessible outside
- [ ] Global for the entire program
- [ ] Dependent on the variable type
- [ ] Dependent on the variable name

# Question 14
What does the `global` keyword do in Python?
- [ ] It defines a variable that is available in all modules
- [x] It enables modification of a global variable within a function
- [ ] It imports a global variable from another module
- [ ] It makes all variables in a function global

# Question 15
What is the output of the following code?
```python
x = 10

def test_function():
    x = 20
    print(x)

test_function()
print(x)
```
- [ ] 10, 10
- [ ] 20, 20
- [x] 20, 10
- [ ] An error is raised

# Question 16
What does the `nonlocal` keyword do in Python?
- [ ] It defines a variable that is available in all functions
- [ ] It imports a variable from another module
- [x] It enables modification of a variable from the enclosing (non-global) scope
- [ ] It prevents a variable from being visible outside the function

# Question 17
What is a lambda function in Python?
- [ ] A function that has multiple return values
- [x] An anonymous function defined in an expression
- [ ] A function that runs automatically
- [ ] A built-in Python function for mathematical operations

# Question 18
Which of the following statements is true for lambda functions in Python?
- [ ] Lambda functions can contain multiple statements
- [ ] Lambda functions can only have one parameter
- [x] Lambda functions consist of a single expression
- [ ] Lambda functions cannot have parameters

# Question 19
What is the correct syntax for a lambda function that calculates the square of a number?
- [x] `lambda x: x**2`
- [ ] `lambda x => x**2`
- [ ] `lambda(x) { return x**2; }`
- [ ] `lambda = x**2`

# Question 20
How do you import a module in Python?
- [ ] `include module`
- [ ] `require module`
- [x] `import module`
- [ ] `using module`

# Question 21
What does the following import statement do?
```python
from math import sin, cos
```
- [ ] Imports the entire math module
- [x] Imports only the sin and cos functions from the math module
- [ ] Creates aliases for the math module
- [ ] Imports all functions except sin and cos from the math module

# Question 22
How do you import a module with an alias?
- [ ] `import module as alias`
- [x] `import module as alias`
- [ ] `import module with alias`
- [ ] `from module import alias`

# Question 23
What is the advantage of using `import module` over `from module import *`?
- [ ] The first variant is faster
- [ ] The first variant imports less code
- [x] The first variant avoids name conflicts in the current namespace
- [ ] There is no difference between the two variants

# Question 24
Which function displays all available names in a module?
- [ ] `list(module)`
- [ ] `help(module)`
- [x] `dir(module)`
- [ ] `names(module)`

# Question 25
What is the purpose of the `if __name__ == "__main__":` block in Python?
- [ ] It defines the main part of the program that always executes
- [x] It enables code to run only when the file is executed directly, not when it's imported as a module
- [ ] It checks if the program is running with administrator rights
- [ ] It marks the beginning of the main function

# Question 26
What is the basic structure for exception handling in Python?
- [ ] `catch-try-finally`
- [x] `try-except-else-finally`
- [ ] `try-catch-finally`
- [ ] `attempt-except-otherwise`

# Question 27
What is defined in the `except` block of a try-except structure?
- [ ] The code to execute after an exception has been handled
- [x] The code to execute when a specific exception occurs
- [ ] The code that must not raise an exception under any circumstances
- [ ] The code to execute when no exception occurs

# Question 28
What is the output of the following code?
```python
try:
    print("A")
    1/0
    print("B")
except ZeroDivisionError:
    print("C")
finally:
    print("D")
```
- [ ] A B D
- [x] A C D
- [ ] A D
- [ ] C D

# Question 29
What is the purpose of the `finally` block in a try-except structure?
- [ ] It only executes if no exception occurs
- [ ] It defines the default action when no `except` clause catches the exception
- [x] It always executes, regardless of whether an exception occurs or not
- [ ] It contains code that executes before the `try` block

# Question 30
What is the purpose of the `else` block in a try-except structure?
- [ ] It always executes, regardless of whether an exception occurs or not
- [x] It only executes if no exception occurs in the `try` block
- [ ] It only executes if an exception occurs in the `try` block
- [ ] It contains alternative code paths for different exception types

# Question 31
Which of the following is NOT a built-in exception in Python?
- [ ] `ValueError`
- [ ] `TypeError`
- [ ] `IndexError`
- [x] `ErrorException`

# Question 32
How do you define a custom exception in Python?
- [ ] By decorating a function with `@exception`
- [x] By creating a class that inherits from `Exception`
- [ ] By using the `raise` keyword with a custom string
- [ ] By importing the `custom_exceptions` module

# Question 33
What is the correct syntax to raise an exception in Python?
- [ ] `throw Exception("Error message")`
- [ ] `except Exception("Error message")`
- [x] `raise Exception("Error message")`
- [ ] `error Exception("Error message")`

# Question 34
How do you catch multiple exception types in a single `except` block?
- [ ] `except ValueError, TypeError:`
- [x] `except (ValueError, TypeError):`
- [ ] `except [ValueError, TypeError]:`
- [ ] `except ValueError and TypeError:`

# Question 35
What is the output of the following code?
```python
try:
    x = int("abc")
except ValueError as e:
    print("A:", e)
except TypeError:
    print("B")
except:
    print("C")
```
- [x] A: invalid literal for int() with base 10: 'abc'
- [ ] B
- [ ] C
- [ ] An error is raised

# Question 36
What is the keyword `as` used for in an `except` block?
- [ ] To define an alternative exception handling code
- [x] To assign the caught exception to a variable
- [ ] To define an alias for the exception type
- [ ] To change the exception handling behavior

# Question 37
What is the hierarchy of exceptions in Python?
- [ ] All exceptions are independent and have no hierarchy
- [x] All exceptions inherit from the base class `BaseException`
- [ ] All exceptions inherit from the base class `Error`
- [ ] The hierarchy depends on the type of error

# Question 38
Which of the following code blocks shows the correct use of `try`, `except`, and `finally`?

- [ ] 
```python
try:
    # Code
catch Exception:
    # Exception handling
endtry
```

- [ ] 
```python
try {
    # Code
} except (Exception) {
    # Exception handling
}
```

- [x] 
```python
try:
    # Code
except Exception:
    # Exception handling
finally:
    # Always executed
```

- [ ] 
```python
try
    # Code
except
    # Exception handling
end
```

# Question 39
What happens when an exception occurs in a `finally` block?
- [ ] The exception is ignored
- [ ] The exception is automatically handled
- [x] The exception overrides any earlier exception in the `try` block
- [ ] The `finally` block is not fully executed

# Question 40
Which statement is correct about the `KeyboardInterrupt` exception?
- [ ] It is raised when an invalid key combination is pressed
- [x] It is raised when the user interrupts the program with Ctrl+C
- [ ] It is raised when a key is pressed while the program is waiting for input
- [ ] It is not a standard Python exception

# Question 41
What is a higher-order function in Python?
- [ ] A function with more than three parameters
- [x] A function that takes other functions as arguments or returns them
- [ ] A function defined in a class
- [ ] A function that is recursive

# Question 42
How can you find out which methods and attributes an imported module has?
- [ ] `help(module)`
- [x] `dir(module)`
- [ ] `module.methods()`
- [ ] `list(module)`

# Question 43
What is a Python package?
- [ ] A collection of Python files in a directory
- [ ] A compressed archive of Python modules
- [x] A directory containing Python modules and a special `__init__.py` file
- [ ] A module that contains multiple classes

# Question 44
Which of the following statements is NOT a valid variation of the import statement in Python?
- [ ] `import module`
- [ ] `from module import function`
- [ ] `from module import *`
- [x] `import module.function`

# Question 45
What is the output of the following code?
```python
def outer():
    x = 1
    def inner():
        nonlocal x
        x = 2
        print("Inner:", x)
    inner()
    print("Outer:", x)

outer()
```
- [ ] Inner: 1, Outer: 1
- [ ] Inner: 2, Outer: 1
- [x] Inner: 2, Outer: 2
- [ ] An error is raised

# Question 46
Which of the following statements about functions in Python is NOT correct?
- [ ] Functions can return other functions
- [ ] Functions can be defined inside other functions
- [ ] Functions can be passed as arguments to other functions
- [x] Functions must have at least one parameter

# Question 47
Which is a valid way to assign a function to a variable in Python?
- [x] `func_var = my_function`
- [ ] `func_var = function(my_function)`
- [ ] `func_var = @my_function`
- [ ] `func_var = def my_function()`

# Question 48
What is the difference between a module and a package in Python?
- [ ] There is no difference, both terms describe the same thing
- [x] A module is a single Python file, a package is a directory with Python files and an __init__.py file
- [ ] A module contains only functions, a package contains classes and objects
- [ ] Modules are part of the standard library, packages must be installed separately

# Question 49
What is the return value of the following function when called with `factorial(4)`?
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)
```
- [ ] 4
- [ ] 12
- [x] 24
- [ ] An error is raised

# Question 50
What is the output of the following code?
```python
def counter():
    count = 0
    def increment():
        nonlocal count
        count += 1
        return count
    return increment

my_counter = counter()
print(my_counter())
print(my_counter())
```
- [ ] 0, 0
- [ ] 0, 1
- [x] 1, 2
- [ ] An error is raised
