# Question 1
What does the parameter `sep` do in the `print()` function?
- [ ] It defines the separator between consecutive `print()` calls
- [x] It defines the separator between multiple arguments of a `print()` function
- [ ] It defines the character set for the output
- [ ] It defines whether the output should be in the terminal or in a file

# Question 2
What is the output of the following code?
```python
print("Python", "is", "cool", sep="-")
```
- [ ] Python is cool
- [x] Python-is-cool
- [ ] Python-is-cool-
- [ ] Pythoniscool

# Question 3
Which parameter of the `print()` function determines what appears at the end of the output?
- [ ] finish
- [ ] separator
- [x] end
- [ ] last

# Question 4
What is the output of the following code?
```python
print("Hello", end="")
print("World")
```
- [ ] Hello
      World
- [x] HelloWorld
- [ ] Hello World
- [ ] HelloWorld\n

# Question 5
What data type does the `input()` function always return?
- [ ] int
- [ ] float
- [ ] The data type depends on the input
- [x] str

# Question 6
How do you correctly convert a number entered by the user into an integer?
- [ ] `integer(input("Enter a number: "))`
- [x] `int(input("Enter a number: "))`
- [ ] `input(int("Enter a number: "))`
- [ ] `convert.int(input("Enter a number: "))`

# Question 7
What happens when a user enters "abc" and you try to convert the input with `int()`?
- [ ] The input is converted to 0
- [ ] The input is converted to an ASCII number
- [x] A ValueError is raised
- [ ] The input remains a string and is not converted

# Question 8
Which of the following string formatting methods is preferred in modern Python?
- [ ] Concatenation with the `+` operator
- [ ] The `%` formatting
- [ ] The `.format()` method
- [x] f-strings

# Question 9
What is the output of the following code?
```python
name = "Max"
age = 25
print(f"{name} is {age} years old.")
```
- [ ] "{name} is {age} years old."
- [ ] "Max is 25 years old"
- [x] Max is 25 years old.
- [ ] name is age years old.

# Question 10
What is the output of the following code?
```python
print("Number: %.2f" % 3.14159)
```
- [ ] Number: 3.14159
- [x] Number: 3.14
- [ ] Number: %.2f
- [ ] Number: 3

# Question 11
Which escape sequence is used for a tab?
- [ ] \s
- [ ] \tab
- [x] \t
- [ ] \b

# Question 12
What is the output of the following code?
```python
print("First line\nSecond line")
```
- [x] First line
      Second line
- [ ] First line\nSecond line
- [ ] First lineSecond line
- [ ] First line Second line

# Question 13
How can you validate user input to ensure that a valid number was entered?
- [ ] The `input()` function does this automatically
- [ ] By using `validateInput()`
- [x] By using try-except blocks with `ValueError`
- [ ] By using the `is_numeric()` function

# Question 14
What is the result of the following code?
```python
text = "Hello {0} and {1}".format("World", "Python")
print(text)
```
- [ ] Hello {0} and {1}
- [ ] Hello and
- [x] Hello World and Python
- [ ] Hello Python and World

# Question 15
Which statement is true?
- [ ] A string can be modified after its creation
- [x] The `.format()` method can use indexed parameters like `{0}`, `{1}`
- [ ] The `input()` function automatically converts the input to a number when possible
- [ ] The `print()` function can process a maximum of 5 arguments

# Question 16
What is the correct syntax for the if statement in Python?
- [ ] if (condition) {code}
- [ ] if condition: then code
- [x] if condition: code
- [ ] if (condition): code:

# Question 17
Which character indicates the beginning of a code block in Python?
- [ ] {
- [ ] begin
- [x] : (colon)
- [ ] [

# Question 18
What is important in Python to define the code block within an if statement?
- [ ] Curly braces around the code
- [ ] The keywords "begin" and "end"
- [x] Correct indentation of the code
- [ ] Semicolons at the end of each line

# Question 19
What is the output of the following code?
```python
x = 5
if x > 3:
    print("A")
if x > 4:
    print("B")
if x == 5:
    print("C")
```
- [ ] A
- [ ] C
- [ ] AB
- [x] ABC

# Question 20
What is the output of the following code?
```python
x = 10
if x > 5:
    print("A")
elif x > 8:
    print("B")
elif x > 12:
    print("C")
else:
    print("D")
```
- [x] A
- [ ] B
- [ ] C
- [ ] D

# Question 21
Which part of an if-elif-else structure is optional?
- [ ] if
- [x] elif and else
- [ ] Only else
- [ ] Only elif

# Question 22
What is the output of the following code?
```python
x = 7
if x > 10:
    print("A")
else:
    if x > 5:
        print("B")
    else:
        print("C")
```
- [ ] A
- [x] B
- [ ] C
- [ ] None of the above

# Question 23
What is the correct syntax for an if-elif-else statement in Python?
- [ ] if (condition1) {code1} elif (condition2) {code2} else {code3}
- [ ] if condition1 then code1 elif condition2 then code2 else code3
- [x] if condition1: code1 elif condition2: code2 else: code3
- [ ] if condition1 do code1 else if condition2 do code2 else do code3

# Question 24
Which of the following statements is equivalent to `x = 5 if y > 0 else 10`?
- [ ] if y > 0 then x = 5 else x = 10
- [x] if y > 0: x = 5 else: x = 10
- [ ] x = (5 if y > 0) ? else 10
- [ ] x = (y > 0) ? 5 : 10

# Question 25
What is the output of the following code?
```python
x = 5
y = 10
print("Yes" if x < y else "No")
```
- [x] Yes
- [ ] No
- [ ] "Yes" if x < y else "No"
- [ ] A syntax error

# Question 26
Which logical operator checks if both conditions are true?
- [ ] ||
- [ ] &
- [x] and
- [ ] &&

# Question 27
What is the result of the expression `True and False`?
- [ ] True
- [x] False
- [ ] None
- [ ] A syntax error

# Question 28
What is the result of the expression `True or False`?
- [x] True
- [ ] False
- [ ] None
- [ ] A syntax error

# Question 29
What does short-circuit evaluation mean for logical operators?
- [ ] The logical operators are evaluated faster than other operators
- [ ] The conditions are evaluated in reverse order
- [x] The second operand is only evaluated if the first operand is not sufficient to determine the result
- [ ] The operands are evaluated simultaneously

# Question 30
What is the result of the following expression?
```python
5 > 3 and 10 > 20
```
- [ ] True
- [x] False
- [ ] An error because the data types are different
- [ ] None

# Question 31
What is the value of `a` after executing the following code?
```python
a = 0
b = 5
if b > 0:
    a = 1
else:
    a = 2
```
- [x] 1
- [ ] 0
- [ ] 2
- [ ] 5

# Question 32
Which logical operator negates a condition?
- [ ] not()
- [ ] !
- [x] not
- [ ] reverse

# Question 33
What is the output of the following code?
```python
x = 5
if x > 0:
    print("A", end="")
    if x > 10:
        print("B", end="")
    else:
        print("C", end="")
print("D")
```
- [ ] AD
- [x] ACD
- [ ] ABD
- [ ] D

# Question 34
Which of the following statements is true regarding the `else` clause?
- [ ] An `else` clause can stand without a preceding `if` statement
- [ ] An `if` statement can have multiple `else` clauses
- [x] The `else` clause is executed when none of the previous conditions are true
- [ ] The `else` clause must always be at the end of a nested `if` structure

# Question 35
What is the output of the following code?
```python
for i in range(3):
    if i == 1:
        break
    print(i, end="")
```
- [x] 0
- [ ] 01
- [ ] 012
- [ ] No output

# Question 36
What is the difference between `==` and `is` in Python?
- [ ] There is no difference, both check for equality
- [ ] `==` is a syntax error, only `is` can be used for comparisons
- [x] `==` checks for value equality, `is` checks for identity (same object)
- [ ] `==` is used for numbers, `is` is used for strings and other objects

# Question 37
What is the output of the following code?
```python
a = True
b = False
c = True
print(a and b or c)
```
- [x] True
- [ ] False
- [ ] A syntax error
- [ ] None

# Question 38
What is the output of the following code?
```python
a = 5
b = 3
print("A" if a > b else "B" if a == b else "C")
```
- [x] A
- [ ] B
- [ ] C
- [ ] A syntax error

# Question 39
Which comparison operator checks for inequality?
- [ ] <>
- [ ] =!
- [x] !=
- [ ] /=

# Question 40
What is the output of the following code?
```python
a = "10"
b = 10
print("Equal" if a == b else "Not equal")
```
- [ ] Equal
- [x] Not equal
- [ ] A TypeError is raised
- [ ] No output

# Question 41
What is the value of `y` after executing the following code?
```python
x = 10
y = 0
if x > 5:
    if x > 15:
        y = 1
    else:
        y = 2
else:
    y = 3
```
- [ ] 0
- [ ] 1
- [x] 2
- [ ] 3

# Question 42
Which statement about short-circuit evaluation for `and` is correct?
- [ ] The second operand is always evaluated
- [x] If the first operand is `False`, the second operand is not evaluated
- [ ] Short-circuit evaluation only works with `or`, not with `and`
- [ ] Short-circuit evaluation is an optimization feature that is not implemented in Python

# Question 43
What is the output of the following code?
```python
print("A", "B", "C", sep=":", end="!")
```
- [ ] A B C!
- [ ] A:B:C
- [x] A:B:C!
- [ ] ABC!

# Question 44
Which of the following is not a valid method for string formatting in Python?
- [ ] `"Name: " + name`
- [ ] `"Name: %s" % name`
- [ ] `"Name: {}".format(name)`
- [x] `"Name: @s".replace("@s", name)`

# Question 45
What is the result of the following code fragment?
```python
a = 5
b = 0
if a > 0:
    b = 1
    if a > 10:
        b = 2
    elif a > 3:
        b = 3
print(b)
```
- [ ] 0
- [ ] 1
- [x] 3
- [ ] 2

# Question 46
What is the priority order of logical operators in Python (from highest to lowest priority)?
- [ ] or, and, not
- [ ] and, or, not
- [x] not, and, or
- [ ] not, or, and

# Question 47
Which of the following statements about conditional expressions in Python is correct?
- [ ] Conditional expressions (ternary operator) were first introduced in Python 3
- [ ] Conditional expressions cannot be combined with logical operators
- [x] A conditional expression has the form `value_if_true if condition else value_if_false`
- [ ] Conditional expressions in Python can only be used for string operations

# Question 48
What is the output of the following code?
```python
x = 0
while x < 3:
    x += 1
    if x == 2:
        continue
    print(x, end="")
```
- [ ] 123
- [x] 13
- [ ] 1
- [ ] 23

# Question 49
What is the correct method to format a string in an f-string so that it has a specific width and is right-aligned?
- [ ] `f"The value is: |{value:>10}|"`
- [ ] `f"The value is: |{value->10}|"`
- [x] `f"The value is: |{value:>10}|"`
- [ ] `f"The value is: |{value:right(10)}|"`

# Question 50
Which of the following conditions is equivalent to `not (a or b)`?
- [ ] not a or not b
- [x] not a and not b
- [ ] not a or b
- [ ] not (a and not b)
