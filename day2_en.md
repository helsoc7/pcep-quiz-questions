# Question 1
What are literals in Python?
- [ ] Variables that can change during program execution
- [x] Fixed values that appear directly in the code
- [ ] Functions that return values
- [ ] Methods for type conversion

# Question 2
Which of the following are valid variable names in Python?
- [x] user_name
- [x] _age
- [ ] 2value
- [ ] class

# Question 3
According to PEP 8, which naming convention is recommended for variables?
- [ ] CamelCase (maxMustermann)
- [x] snake_case (max_mustermann)
- [ ] UPPERCASE (MAXMUSTERMANN)
- [ ] PascalCase (MaxMustermann)

# Question 4
Which of the following statements about variables in Python are correct?
- [x] Variable names are case-sensitive
- [x] Variable names can contain underscores
- [ ] Variable names must begin with a letter
- [ ] Python keywords can be used as variable names

# Question 5
What is the difference between variables and literals?
- [ ] Literals can only be numbers, variables can contain any values
- [ ] Variables are created at runtime, literals at compile time
- [x] Variables are named memory locations, literals are fixed values in the code
- [ ] There is no difference, both terms describe the same thing

# Question 6
What value results from the following operation?

```python
int(float("3.14"))
```
- [x] 3
- [ ] 3.14
- [ ] 4
- [ ] This leads to a ValueError

# Question 7
Which of the following statements about type conversion in Python are true?
- [x] `int("42")` converts the string "42" to the integer 42
- [x] `bool(0)` returns False
- [ ] `int("3.14")` converts the string "3.14" to the integer 3
- [ ] `str(True)` returns "1"

# Question 8
What is the result of `bool("")`?
- [x] False
- [ ] True
- [ ] ""
- [ ] None

# Question 9
Which of the following values are interpreted as `False` in a boolean context?
- [x] 0
- [x] ""
- [x] []
- [ ] "False"

# Question 10
How do you check in Python if a variable has the type Integer?
- [ ] `variable.type() == int`
- [ ] `type(variable) == "int"`
- [x] `isinstance(variable, int)`
- [ ] `isint(variable)`

# Question 11
What is the result of the expression `0b101010`?
- [ ] 101010
- [ ] 12
- [x] 42
- [ ] A syntax error

# Question 12
Which statement about the range of Integers in Python is correct?
- [ ] Integers are limited to 32 bits (from -2^31 to 2^31-1)
- [ ] Integers are limited to 64 bits (from -2^63 to 2^63-1)
- [x] Integers have an unlimited range
- [ ] Integers can only store positive values

# Question 13
What is the value of `1_000_000` in Python?
- [x] 1000000
- [ ] 1_000_000
- [ ] A syntax error
- [ ] 100000

# Question 14
What is the result of the expression `0.1 + 0.2 == 0.3` in Python?
- [ ] True
- [x] False
- [ ] A syntax error
- [ ] Depends on the Python version

# Question 15
Which code produces the value "infinity" in Python?
- [ ] infinity()
- [ ] Integer.MAX_VALUE
- [x] float('inf')
- [ ] math.infinity

# Question 16
How do you access the first character of a string `text`?
- [ ] text(0)
- [x] text[0]
- [ ] text.first()
- [ ] text.charAt(0)

# Question 17
What does the following code output?

```python
print("Python"[::-1])
```
- [ ] Python
- [ ] P
- [ ] nohtyP
- [x] nohtyP

# Question 18
Which method is used to convert a string to lowercase?
- [ ] toLower()
- [ ] lowercase()
- [x] lower()
- [ ] small()

# Question 19
Which is the recommended method for string formatting in modern Python?
- [ ] %-formatting
- [ ] format() method
- [x] f-strings
- [ ] template.substitute()

# Question 20
What result does `len("Python")` return?
- [ ] 5
- [x] 6
- [ ] 7
- [ ] An error, since len() doesn't work for strings

# Question 21
Which statement about multi-line strings in Python is correct?
- [ ] Multi-line strings can only be created with the escape character \n
- [ ] Multi-line strings can only be created by concatenating strings
- [x] Multi-line strings can be created with triple quotes (''' or """)
- [ ] Python doesn't support multi-line strings

# Question 22
What is the result of `"abc" * 3`?
- [x] "abcabcabc"
- [ ] "abc3"
- [ ] A TypeError
- [ ] 9

# Question 23
Which method is used to split a string into a list of substrings?
- [ ] divide()
- [ ] partition()
- [x] split()
- [ ] tokenize()

# Question 24
What is the value of `5 // 2` in Python?
- [ ] 2.5
- [x] 2
- [ ] 3
- [ ] 2.0

# Question 25
Which operator is used for exponentiation in Python?
- [ ] ^
- [ ] *^
- [ ] pow()
- [x] **

# Question 26
What is the result of `2 + 3 * 4`?
- [ ] 20
- [x] 14
- [ ] 10
- [ ] 24

# Question 27
Which expression is equivalent to `x += 5`?
- [x] x = x + 5
- [ ] x = x * 5
- [ ] x = 5
- [ ] x = 5 + x

# Question 28
What is the value of `10 % 3`?
- [ ] 3
- [ ] 3.33
- [x] 1
- [ ] 0

# Question 29
What is the correct operator precedence in Python (from highest to lowest priority)?
- [ ] Assignments, arithmetic operations, parentheses
- [ ] Parentheses, assignments, arithmetic operations
- [x] Parentheses, exponentiation, multiplication/division, addition/subtraction, assignments
- [ ] Addition/subtraction, multiplication/division, exponentiation, parentheses

# Question 30
What is the result of `True + True` in Python?
- [ ] True
- [x] 2
- [ ] 1
- [ ] A TypeError

# Question 31
What is the result of `5 > 3 and 10 < 20`?
- [x] True
- [ ] False
- [ ] None
- [ ] A syntax error

# Question 32
What is the result of `not (5 > 7)`?
- [x] True
- [ ] False
- [ ] None
- [ ] A syntax error

# Question 33
What is the result of `0 < 5 < 10` in Python?
- [x] True
- [ ] False
- [ ] A syntax error
- [ ] Depends on the Python version

# Question 34
Which logical operator is used for the OR connection?
- [ ] ||
- [x] or
- [ ] OR
- [ ] |

# Question 35
What does the term "short-circuit evaluation" mean for logical operators?
- [ ] The evaluation happens particularly fast
- [ ] Logical operators have a higher priority than other operators
- [x] The second operand is evaluated only if the first one is not sufficient to determine the result
- [ ] The evaluation takes place from right to left

# Question 36
What is the result of `True or print("Hello")`?
- [x] True
- [ ] Hello
- [ ] True and Hello is printed
- [ ] A syntax error

# Question 37
Which operator combination can be used to check if x is between 10 and 20 (inclusive)?
- [ ] 10 < x < 20
- [x] 10 <= x <= 20
- [ ] x >= 10 and x <= 20
- [ ] Both 10 <= x <= 20 and x >= 10 and x <= 20 are correct

# Question 38
What is the result of `int(3.99)` in Python?
- [x] 3
- [ ] 4
- [ ] 3.0
- [ ] A ValueError

# Question 39
Which of the following statements results in a ValueError?
- [ ] `int("42")`
- [ ] `float("3.14")`
- [x] `int("3.14")`
- [ ] `bool("False")`

# Question 40
What is the result of `set([1, 2, 2, 3, 3, 3])`?
- [ ] [1, 2, 2, 3, 3, 3]
- [ ] [1, 2, 3]
- [x] {1, 2, 3}
- [ ] A TypeError

# Question 41
Which function returns the data type of an object?
- [x] type()
- [ ] typeof()
- [ ] gettype()
- [ ] datatype()

# Question 42
What is the result of `type(5)`?
- [ ] "int"
- [ ] int
- [x] <class 'int'>
- [ ] integer

# Question 43
What does the `isdigit()` method return for a string?
- [ ] The number of digits in the string
- [x] True, if the string consists only of digits
- [ ] The first numeric value in the string
- [ ] A list of all digits in the string

# Question 44
What property do all strings in Python have?
- [ ] They can be modified after creation
- [x] They are immutable
- [ ] They have a maximum length of 255 characters
- [ ] They can only contain ASCII characters

# Question 45
What is the difference between `==` and `is` in Python?
- [ ] There is no difference, both check for equality
- [ ] `==` checks for equality, `is` is not a valid Python operator
- [x] `==` checks for value equality, `is` checks for identity (same object)
- [ ] `==` only works for numeric types, `is` works for all types

# Question 46
Which is a valid way to define a raw string in Python?
- [x] r"C:\Users\Name"
- [ ] raw"C:\Users\Name"
- [ ] "C:\\Users\\Name"
- [ ] raw("C:\Users\Name")

# Question 47
What is the result of executing the following code?

```python
a = "Python"
a[0] = "J"
print(a)
```
- [ ] "Jython"
- [ ] "Python"
- [x] A TypeError, since strings are immutable
- [ ] An IndexError

# Question 48
Which statement about boolean values in Python is correct?
- [ ] Python has no special boolean data types
- [ ] Boolean values are represented by 0 and 1
- [x] True and False are special boolean values with capital letters
- [ ] True and False are normal strings

# Question 49
What does the following line of code output?

```python
print("Python"[1:4])
```
- [ ] "Pyt"
- [x] "yth"
- [ ] "ytho"
- [ ] "ython"

# Question 50
How can you check in Python if a string consists only of letters?
- [ ] `string.only_letters()`
- [ ] `letters_only(string)`
- [x] `string.isalpha()`
- [ ] `string.alpha()`
