# Question 1
What is the result of the following expression in Python?
```python
print(3 * 'abc' + 'def')
```
- [ ] abcabcabcdef
- [x] abcabcabcdef
- [ ] abc3def
- [ ] 3abcdef

# Question 2
What is the primary purpose of the `pass` statement in Python?
- [ ] To pass a value from one function to another
- [ ] To skip the current iteration in a loop
- [x] To serve as a placeholder when a statement is syntactically required but no action is needed
- [ ] To terminate program execution

# Question 3
Which of the following is the correct way to define a function with a default parameter value?
- [ ] `def function(param = default_value):`
- [x] `def function(param=default_value):`
- [ ] `def function(param:default_value):`
- [ ] `def function(param<-default_value):`

# Question 4
What will be the output of the following code?
```python
numbers = [10, 20, 30]
numbers.append([40, 50])
print(len(numbers))
```
- [ ] 5
- [x] 4
- [ ] 3
- [ ] An error is raised

# Question 5
Which statement correctly describes Python's global scope?
- [ ] Variables in global scope can be accessed and modified from any function without special keywords
- [ ] Variables in global scope cannot be accessed from functions
- [x] Variables in global scope can be accessed from any function, but require the `global` keyword to be modified
- [ ] Each module has its own separate global scope that cannot be accessed by other modules

# Question 6
What does the following code snippet do?
```python
s = 'Python Programming'
result = s.swapcase()
```
- [ ] Swaps the first and last characters of the string
- [x] Changes lowercase letters to uppercase and uppercase to lowercase
- [ ] Reverses the entire string
- [ ] Sorts the characters alphabetically

# Question 7
What is the output of the following code?
```python
for i in range(1, 11):
    if i == 5:
        continue
    if i == 8:
        break
    print(i, end=' ')
```
- [ ] 1 2 3 4 5 6 7 8 9 10
- [ ] 1 2 3 4 6 7 8 9 10
- [x] 1 2 3 4 6 7
- [ ] 1 2 3 4 5 6 7

# Question 8
What is the type of the variable `x` after the following assignment?
```python
x = 3 // 2
```
- [ ] float
- [x] int
- [ ] bool
- [ ] complex

# Question 9
In Python, what does the `strip()` method do when called on a string?
- [ ] It removes all spaces from the string
- [ ] It removes all punctuation from the string
- [x] It removes leading and trailing whitespace from the string
- [ ] It divides the string into a list of characters

# Question 10
What is the output of the following code?
```python
def modify_list(lst):
    lst.append(4)
    lst = [7, 8, 9]
    return lst

my_list = [1, 2, 3]
new_list = modify_list(my_list)
print(my_list, new_list)
```
- [ ] [1, 2, 3] [7, 8, 9]
- [x] [1, 2, 3, 4] [7, 8, 9]
- [ ] [1, 2, 3, 4] [1, 2, 3, 4]
- [ ] [7, 8, 9] [7, 8, 9]

# Question 11
What is the value of the variable `result` after the following code executes?
```python
result = 'python'[1::2]
```
- [ ] pto
- [x] yhn
- [ ] yto
- [ ] phn

# Question 12
How can you convert a floating-point number to an integer in Python, discarding the decimal part?
- [ ] `round(number)`
- [x] `int(number)`
- [ ] `floor(number)`
- [ ] `truncate(number)`

# Question 13
What is the output of the following code?
```python
my_dict = {'a': 1, 'b': 2}
my_dict.setdefault('c', 3)
print(my_dict)
```
- [ ] {'a': 1, 'b': 2}
- [x] {'a': 1, 'b': 2, 'c': 3}
- [ ] {'a': 1, 'b': 2, 'c': None}
- [ ] An error is raised

# Question 14
Which of the following statements is correct about Python's string immutability?
- [ ] String immutability means that strings are constantly changing
- [ ] String immutability means that strings cannot be used in loops
- [x] String immutability means that you cannot change an existing string's content
- [ ] String immutability is an optional feature that can be disabled

# Question 15
What is the output of the following code?
```python
def func(x=[]):
    x.append(1)
    return x

print(func())
print(func())
```
- [ ] [1] [1]
- [x] [1] [1, 1]
- [ ] [] [1]
- [ ] A syntax error occurs

# Question 16
Which of the following correctly creates a dictionary using a dictionary comprehension?
- [ ] `{x, x*x for x in range(5)}`
- [x] `{x: x*x for x in range(5)}`
- [ ] `{for x in range(5): x, x*x}`
- [ ] `dict(x, x*x for x in range(5))`

# Question 17
Which of the following statements is TRUE about Python's `is` operator?
- [ ] `is` checks if two variables have the same value
- [x] `is` checks if two variables reference the same object in memory
- [ ] `is` is an alias for the assignment operator `=`
- [ ] `is` checks if a variable exists in the current scope

# Question 18
In Python, what happens if you try to access a key that doesn't exist in a dictionary?
- [ ] The dictionary automatically creates the key with a None value
- [ ] The program continues with no effect
- [x] A KeyError is raised
- [ ] The dictionary returns a default empty value

# Question 19
What does the following code output?
```python
text = "Python"
print(text.ljust(10, '*'))
```
- [ ] *****Python
- [x] Python****
- [ ] **Python**
- [ ] Python*****

# Question 20
What is the output of the following code?
```python
numbers = list(range(5))
print(sum(numbers))
```
- [ ] 5
- [ ] 4
- [x] 10
- [ ] 15

# Question 21
Which statement about Python list operations is correct?
- [ ] You cannot mix different data types in a single list
- [ ] Lists in Python have a fixed size once created
- [x] The `pop()` method removes and returns an element from a list
- [ ] Lists are immutable like strings

# Question 22
What will be the result of the following expression?
```python
any([0, False, "", None, [], 5])
```
- [x] True
- [ ] False
- [ ] None
- [ ] 5

# Question 23
Which of the following is NOT a valid way to create an empty set in Python?
- [ ] `set()`
- [ ] `{*()}`
- [x] `{}`
- [ ] `set([])`

# Question 24
What is the output of the following code?
```python
def greet(name, message="Hello"):
    return f"{message}, {name}!"
    
print(greet("John", message="Hi"))
```
- [ ] Hello, John!
- [x] Hi, John!
- [ ] John, Hi!
- [ ] A TypeError is raised

# Question 25
Which of the following statements is correct about Python's `all()` function?
- [ ] `all()` returns True if any element in the iterable is True
- [x] `all()` returns True if all elements in the iterable are True
- [ ] `all()` returns the first element in the iterable
- [ ] `all()` returns the sum of all elements in the iterable

# Question 26
What will the following code print?
```python
list1 = [1, 2, 3]
list2 = list1
list1[0] = 4
print(list2)
```
- [ ] [1, 2, 3]
- [x] [4, 2, 3]
- [ ] [4, 2, 3, 1, 2, 3]
- [ ] An error is raised

# Question 27
Which function would you use to find the largest value in a sequence?
- [ ] `largest()`
- [x] `max()`
- [ ] `big()`
- [ ] `top()`

# Question 28
What is the correct way to create a new sorted list from an existing list without modifying the original list?
- [ ] `new_list = list.sort()`
- [x] `new_list = sorted(list)`
- [ ] `new_list = list.sorted()`
- [ ] `new_list = sort(list)`

# Question 29
What is the result of the following expression?
```python
'hello'.find('l')
```
- [ ] 0
- [ ] -1
- [x] 2
- [ ] [2, 3]

# Question 30
What is the output of the following code?
```python
def outer_function():
    x = 10
    def inner_function():
        nonlocal x
        x = 20
    inner_function()
    return x

print(outer_function())
```
- [ ] 10
- [x] 20
- [ ] A NameError is raised
- [ ] None

# Question 31
What will be the output of the following code?
```python
word = "Python Programming"
print(word.count('P'))
```
- [ ] 0
- [x] 2
- [ ] 1
- [ ] A ValueError is raised

# Question 32
Which statement is correct about Python modules?
- [ ] A module is the same as a function
- [ ] Modules can only be written in Python
- [x] Modules are files containing Python definitions and statements
- [ ] Each Python program can only import one module

# Question 33
What is the output of the following code?
```python
fruits = ['apple', 'banana', 'cherry']
print('apple' in fruits)
```
- [x] True
- [ ] False
- [ ] 'apple'
- [ ] 0

# Question 34
What is the value of the variable `result` after the following code executes?
```python
numbers = [1, 2, 3, 4, 5]
result = list(filter(lambda x: x % 2 == 0, numbers))
```
- [ ] [1, 3, 5]
- [x] [2, 4]
- [ ] [True, False, True, False, True]
- [ ] []

# Question 35
What is the purpose of the Python `zip()` function?
- [ ] To compress files and folders
- [x] To combine elements from multiple iterables into tuples
- [ ] To convert numbers to strings
- [ ] To create a list of consecutive integers

# Question 36
Which of the following is a built-in Python function that returns a series of consecutive integers?
- [ ] `consecutive()`
- [x] `range()`
- [ ] `sequence()`
- [ ] `series()`

# Question 37
What will be the result of the following expression?
```python
min(max(3, 4), max(8, 2))
```
- [ ] 2
- [ ] 3
- [x] 4
- [ ] 8

# Question 38
How would you round the number 7.6345 to two decimal places in Python?
- [x] `round(7.6345, 2)`
- [ ] `round(7.6345, 2, 0)`
- [ ] `format(7.6345, '.2')`
- [ ] `int(7.6345 * 100) / 100`

# Question 39
Which of the following best describes what a Python package is?
- [ ] A compressed archive of Python code
- [x] A directory containing Python modules and a special __init__.py file
- [ ] A single Python file that defines multiple classes
- [ ] A collection of Python variables

# Question 40
What is the output of the following code?
```python
def calculate(a, b, operation='add'):
    if operation == 'add':
        return a + b
    elif operation == 'multiply':
        return a * b
    else:
        return None

print(calculate(5, 3, 'multiply'))
```
- [ ] 8
- [x] 15
- [ ] 2
- [ ] None

# Question 41
What does the `enumerate()` function do in Python?
- [ ] It creates a numbered list
- [x] It returns a tuple containing the count and the element from an iterable
- [ ] It checks if a container has numeric elements
- [ ] It counts the total number of elements in an iterable

# Question 42
What is the output of the following code?
```python
data = {'a': 1, 'b': 2}
print(data.get('c', 3))
```
- [ ] {'a': 1, 'b': 2, 'c': 3}
- [ ] None
- [x] 3
- [ ] A KeyError is raised

# Question 43
Which method can you use to count the number of items in a list?
- [ ] `size()`
- [x] `len()`
- [ ] `count()`
- [ ] `length()`

# Question 44
What is the correct syntax for a Python list comprehension that filters odd numbers from a list?
- [ ] `[if x % 2 != 0 then x for x in numbers]`
- [x] `[x for x in numbers if x % 2 != 0]`
- [ ] `[x if x % 2 != 0 for x in numbers]`
- [ ] `[for x in numbers if x % 2 != 0: x]`

# Question 45
What happens when the following code is executed?
```python
my_list = [1, 2, 3]
my_list.insert(10, 4)
print(my_list)
```
- [ ] An IndexError is raised
- [ ] The number 4 is inserted at index 10, and None values fill positions 3-9
- [x] The number 4 is added to the end of the list
- [ ] The operation is ignored and the list remains unchanged

# Question 46
Which built-in function would you use to create a dictionary from two lists, one containing keys and the other containing values?
- [ ] `merge()`
- [ ] `combine()`
- [x] `zip()`
- [ ] `dict_from_lists()`

# Question 47
What is the output of the following code?
```python
text = "Python"
for i, char in enumerate(text):
    if char == 'h':
        print(i)
```
- [ ] P
- [ ] h
- [x] 3
- [ ] 4

# Question 48
Which of the following statements correctly defines a lambda function in Python?
- [ ] `lambda x = x * 2`
- [x] `lambda x: x * 2`
- [ ] `def lambda(x): x * 2`
- [ ] `lambda: x = x * 2`

# Question 49
What does the Python function `dir()` do when called with no arguments?
- [ ] Returns the current working directory path
- [ ] Returns a list of all Python keywords
- [x] Returns a list of names in the current local scope
- [ ] Displays the Python documentation

# Question 50
If a function does not explicitly return a value in Python, what is returned by default?
- [ ] 0
- [ ] False
- [x] None
- [ ] An empty string
