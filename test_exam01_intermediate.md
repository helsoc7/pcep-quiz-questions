# Question 1
What is the output of the following code?
```python
x = 10
y = 5
print(x % y, x // y)
```
- [ ] 0 2.0
- [x] 0 2
- [ ] 0.0 2
- [ ] 2 0

# Question 2
Which of the following correctly describes string slicing in Python?
- [ ] String slicing always includes both the start and end indices
- [x] String slicing includes the start index but excludes the end index
- [ ] String slicing excludes both the start and end indices
- [ ] String slicing works only with positive indices

# Question 3
What does the following code print?
```python
words = ["apple", "banana", "cherry"]
words.insert(1, "orange")
print(words[2])
```
- [ ] apple
- [ ] orange
- [x] banana
- [ ] cherry

# Question 4
What is the result of the expression `"Python"[::-1]`?
- [ ] "Python"
- [ ] "Python"
- [x] "nohtyP"
- [ ] "P"

# Question 5
Which statement about Python's `in` operator is correct?
- [ ] It can only be used with lists
- [ ] It always returns an index where the element is found
- [x] It can be used to check if an element exists in a sequence
- [ ] It modifies the sequence by adding an element

# Question 6
What is the output of the following code?
```python
numbers = [1, 2, 3, 4]
total = 0
for num in numbers:
    if num % 2 == 0:
        total += num
print(total)
```
- [ ] 10
- [x] 6
- [ ] 4
- [ ] 2

# Question 7
What does the `strip()` method do when called on a string?
- [ ] It removes all whitespace from the string
- [x] It removes leading and trailing whitespace
- [ ] It removes all spaces between words
- [ ] It capitalizes the first letter of each word

# Question 8
What will be the value of `x` after the following code executes?
```python
x = 1
for i in range(3):
    x *= 2
```
- [ ] 3
- [ ] 6
- [x] 8
- [ ] 9

# Question 9
Which of the following statements about Python dictionaries is TRUE?
- [ ] Dictionary keys must be strings
- [ ] Dictionaries preserve the order of elements as they are added (in all Python versions)
- [x] Dictionary keys must be immutable objects
- [ ] Dictionaries cannot contain other dictionaries as values

# Question 10
What is the output of the following code?
```python
def modify(lst):
    lst.append(4)
    
numbers = [1, 2, 3]
modify(numbers)
print(numbers)
```
- [ ] [1, 2, 3]
- [x] [1, 2, 3, 4]
- [ ] [4, 1, 2, 3]
- [ ] An error is raised

# Question 11
What is the result of the following expression?
```python
', '.join(['apple', 'banana', 'cherry'])
```
- [ ] ['apple, banana, cherry']
- [x] 'apple, banana, cherry'
- [ ] 'apple', 'banana', 'cherry'
- [ ] 'apple,banana,cherry'

# Question 12
Which function is used to find the minimum value in a sequence?
- [ ] `smallest()`
- [x] `min()`
- [ ] `lowest()`
- [ ] `minimum()`

# Question 13
What is the output of the following code?
```python
print(bool([]), bool(""), bool(0), bool(None))
```
- [ ] True True True True
- [ ] False False False False
- [x] False False False False
- [ ] True False True False

# Question 14
What does the following code print?
```python
data = {'a': 1, 'b': 2}
data['c'] = data.get('a', 0) + data.get('b', 0)
print(data['c'])
```
- [ ] 0
- [ ] 1
- [ ] 2
- [x] 3

# Question 15
What is the correct way to convert a string to title case (first letter of each word capitalized)?
- [ ] `str.upper()`
- [ ] `str.capital()`
- [x] `str.title()`
- [ ] `str.capitalize()`

# Question 16
What is the output of the following code?
```python
def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)
        
print(factorial(4))
```
- [ ] 12
- [x] 24
- [ ] 64
- [ ] 4

# Question 17
Which of the following is the correct way to open a file named "data.txt" for reading in Python?
- [x] `f = open("data.txt", "r")`
- [ ] `f = open("data.txt", "read")`
- [ ] `f = read("data.txt")`
- [ ] `f = file.open("data.txt")`

# Question 18
What will happen when the following code is executed?
```python
for i in range(3):
    try:
        if i == 1:
            continue
        print(i, end=" ")
    finally:
        print("done", end=" ")
```
- [ ] 0 1 2 done
- [ ] 0 done 2 done
- [x] 0 done done 2 done
- [ ] An error occurs

# Question 19
What is the output of the following code?
```python
numbers = list(range(1, 6))
print(numbers[1:-1])
```
- [ ] [1, 2, 3, 4]
- [x] [2, 3, 4]
- [ ] [2, 3, 4, 5]
- [ ] [1, 5]

# Question 20
What will the following code print?
```python
d = {"a": 1, "b": 2, "c": 3}
for k, v in d.items():
    if v == 2:
        print(k)
```
- [ ] a
- [x] b
- [ ] c
- [ ] None

# Question 21
What does the `enumerate()` function return in Python?
- [ ] A list of indices for the iterable
- [ ] A count of how many elements are in the iterable
- [x] An iterator that produces tuples containing indices and values
- [ ] A boolean indicating if all elements are enumerable

# Question 22
What is the output of the following code?
```python
a = [1, 2, 3]
b = a
a[0] = 5
print(b)
```
- [ ] [1, 2, 3]
- [x] [5, 2, 3]
- [ ] [1, 2, 3, 5]
- [ ] Error

# Question 23
Which of the following is a valid way to create a dictionary in Python?
- [ ] `dict(a=1, b=2, c=3)`
- [ ] `{"a": 1, "b": 2, "c": 3}`
- [ ] `dict([("a", 1), ("b", 2), ("c", 3)])`
- [x] All of the above

# Question 24
What is the output of the following code?
```python
text = "Python is fun"
words = text.split()
print(len(words))
```
- [ ] 10
- [ ] 11
- [x] 3
- [ ] 2

# Question 25
What is the result of the following expression?
```python
[x*2 for x in range(1, 5) if x % 2 == 0]
```
- [ ] [2, 4, 6, 8]
- [x] [4, 8]
- [ ] [2, 6]
- [ ] [4]

# Question 26
What happens when the following code is executed?
```python
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"

print(greet("John"))
```
- [ ] The function returns "John, Hello!"
- [x] The function returns "Hello, John!"
- [ ] An error occurs because the second parameter is missing
- [ ] The function returns "Hello, !"

# Question 27
What is the output of the following code?
```python
total = 0
for i in range(1, 5):
    if i % 2 == 0:
        continue
    total += i
print(total)
```
- [ ] 10
- [ ] 6
- [x] 4
- [ ] 0

# Question 28
Which method would you use to check if a string contains only alphabetic characters?
- [ ] `str.alpha()`
- [x] `str.isalpha()`
- [ ] `str.isalnum()`
- [ ] `str.contains_alpha()`

# Question 29
What will be the output of the following code?
```python
numbers = [1, 2, 3, 4, 5]
result = numbers.pop(2)
print(result, numbers)
```
- [ ] 2 [1, 3, 4, 5]
- [x] 3 [1, 2, 4, 5]
- [ ] 3 [1, 2, 3, 4]
- [ ] 5 [1, 2, 3, 4]

# Question 30
What is the output of the following code?
```python
def change_list(my_list):
    my_list = [10, 20, 30]
    
original = [1, 2, 3]
change_list(original)
print(original)
```
- [x] [1, 2, 3]
- [ ] [10, 20, 30]
- [ ] [1, 2, 3, 10, 20, 30]
- [ ] []

# Question 31
What is the result of the following expression?
```python
set('Hello') & set('World')
```
- [ ] {'H', 'e', 'l', 'o', 'W', 'r', 'd'}
- [ ] {'h', 'e', 'l', 'o', 'w', 'r', 'd'}
- [x] {'o', 'l'}
- [ ] set()

# Question 32
What does the `any()` function in Python return?
- [ ] True if all elements in the iterable are True
- [x] True if at least one element in the iterable is True
- [ ] The first True element in the iterable
- [ ] The number of True elements in the iterable

# Question 33
What is the output of the following code?
```python
print('abc'.center(7, '*'))
```
- [ ] abc****
- [ ] ****abc
- [x] **abc**
- [ ] ***abc***

# Question 34
Which of the following methods removes and returns the last item from a list?
- [ ] `list.remove()`
- [ ] `list.delete()`
- [x] `list.pop()`
- [ ] `list.discard()`

# Question 35
What is the output of the following code?
```python
x = [1, 2, 3]
y = x.copy()
x.append(4)
print(y)
```
- [ ] [1, 2, 3, 4]
- [x] [1, 2, 3]
- [ ] [4, 1, 2, 3]
- [ ] []

# Question 36
What does the `sorted()` function return?
- [ ] It sorts the original sequence and returns None
- [x] It returns a new sorted list without modifying the original sequence
- [ ] It returns a tuple of sorted elements
- [ ] It returns the largest element in the sequence

# Question 37
What will the following code print?
```python
def func(a=[], b={}):
    print(f"a={a}, b={b}")
    
func()
func([1, 2], {"x": 1})
```
- [ ] a=None, b=None
     a=[1, 2], b={'x': 1}
- [x] a=[], b={}
     a=[1, 2], b={'x': 1}
- [ ] a=[], b={}
     a=[], b={}
- [ ] Error

# Question 38
What is the output of the following code?
```python
def outer():
    x = 1
    def inner():
        x = 2
        print("inner:", x)
    inner()
    print("outer:", x)
    
outer()
```
- [ ] inner: 1
     outer: 2
- [x] inner: 2
     outer: 1
- [ ] inner: 2
     outer: 2
- [ ] inner: 1
     outer: 1

# Question 39
What is the output of the following code?
```python
for i in range(3):
    for j in range(2):
        if i == j:
            print("*", end="")
        else:
            print("-", end="")
```
- [ ] **----
- [x] *-*-*-
- [ ] -*-*-*
- [ ] ------

# Question 40
What will the following code print?
```python
words = ["apple", "banana", "cherry"]
print("-".join(words))
```
- [ ] apple, banana, cherry
- [ ] ["apple-banana-cherry"]
- [x] apple-banana-cherry
- [ ] apple/banana/cherry

# Question 41
If `a = [1, 2, 3]` and `b = [4, 5, 6]`, what will `a + b` return?
- [ ] [5, 7, 9]
- [x] [1, 2, 3, 4, 5, 6]
- [ ] [[1, 2, 3], [4, 5, 6]]
- [ ] Error

# Question 42
What is the output of the following code?
```python
my_dict = {"a": 1, "b": 2}
for item in my_dict:
    print(item, end=" ")
```
- [ ] 1 2
- [x] a b
- [ ] ("a", 1) ("b", 2)
- [ ] a:1 b:2

# Question 43
What is the output of the following code?
```python
numbers = [10, 20, 30, 40]
numbers[1:3] = [200, 300]
print(numbers)
```
- [ ] [10, 20, 30, 40]
- [ ] [10, 200, 300]
- [x] [10, 200, 300, 40]
- [ ] [10, [200, 300], 40]

# Question 44
What is the result of `float("3.14") + int("2")`?
- [ ] "3.142"
- [ ] 3.142
- [x] 5.14
- [ ] Error

# Question 45
What does the `all()` function in Python return?
- [ ] True if any element in the iterable is True
- [x] True if all elements in the iterable are True
- [ ] The number of True elements in the iterable
- [ ] The first False element in the iterable

# Question 46
What is the output of the following code?
```python
a = [1, 2, 3]
b = (a,)
a.append(4)
print(b)
```
- [ ] ([1, 2, 3],)
- [x] ([1, 2, 3, 4],)
- [ ] ([1, 2, 3], 4)
- [ ] [1, 2, 3, 4]

# Question 47
What is the output of the following code?
```python
print(sorted(['apple', 'Banana', 'cherry']))
```
- [ ] ['apple', 'Banana', 'cherry']
- [ ] ['apple', 'banana', 'cherry']
- [x] ['Banana', 'apple', 'cherry']
- [ ] ['banana', 'apple', 'cherry']

# Question 48
What will the following code print?
```python
def func(a, b, *args, **kwargs):
    print(len(args) + len(kwargs))
    
func(1, 2, 3, 4, x=5, y=6)
```
- [ ] 6
- [ ] 2
- [x] 4
- [ ] 5

# Question 49
What is the output of the following code?
```python
for i in range(5):
    if i % 2 == 0:
        pass
    else:
        print(i, end=" ")
```
- [ ] 0 2 4
- [x] 1 3
- [ ] 0 1 2 3 4
- [ ] No output

# Question 50
What is the output of the following code?
```python
words = ["hi" if i % 2 == 0 else "hello" for i in range(4)]
print(words)
```
- [ ] ["hi", "hi", "hi", "hi"]
- [ ] ["hello", "hello", "hello", "hello"]
- [x] ["hi", "hello", "hi", "hello"]
- [ ] ["hi, "hello"]
