# Question 1
What is the difference between lists and tuples in Python?
- [ ] Lists can only contain numbers, tuples can contain any data types
- [ ] Lists are faster than tuples
- [x] Lists are mutable, tuples are immutable
- [ ] Tuples can contain more elements than lists

# Question 2
How do you create an empty list in Python?
- [x] `my_list = []` or `my_list = list()`
- [ ] `my_list = {}`
- [ ] `my_list = ()`
- [ ] `my_list = new List()`

# Question 3
What is the output of the following code?
```python
numbers = [1, 2, 3, 4, 5]
print(numbers[1:4])
```
- [ ] [1, 2, 3, 4]
- [x] [2, 3, 4]
- [ ] [1, 2, 3]
- [ ] [2, 3]

# Question 4
How do you add an element to the end of a list?
- [ ] `list.insert(element)`
- [x] `list.append(element)`
- [ ] `list.add(element)`
- [ ] `list.extend(element)`

# Question 5
What does the `extend()` method do with lists?
- [ ] It increases the capacity of the list
- [ ] It adds an element multiple times
- [x] It adds all elements of an iterable object to the list
- [ ] It extends a list by a specific number of empty elements

# Question 6
What is the output of the following code?
```python
fruits = ["Apple", "Banana", "Cherry"]
fruits.insert(1, "Orange")
print(fruits)
```
- [ ] ["Orange", "Apple", "Banana", "Cherry"]
- [x] ["Apple", "Orange", "Banana", "Cherry"]
- [ ] ["Apple", "Banana", "Orange", "Cherry"]
- [ ] An error is raised

# Question 7
Which method removes an element from a list and returns the value?
- [ ] `remove()`
- [x] `pop()`
- [ ] `delete()`
- [ ] `extract()`

# Question 8
What is the result of the following expression?
```python
[1, 2, 3] + [4, 5, 6]
```
- [x] [1, 2, 3, 4, 5, 6]
- [ ] [5, 7, 9]
- [ ] [[1, 2, 3], [4, 5, 6]]
- [ ] An error is raised

# Question 9
How do you create a list with numbers from 1 to 10?
- [ ] `range(1, 10)`
- [x] `list(range(1, 11))`
- [ ] `list(range(10))`
- [ ] `[1-10]`

# Question 10
What is the output of the following code?
```python
numbers = [10, 20, 30, 40, 50]
print(numbers[-2])
```
- [ ] -2
- [ ] 20
- [x] 40
- [ ] An error is raised

# Question 11
How do you sort a list in ascending order?
- [ ] `sort(list)`
- [x] `list.sort()` or `sorted(list)`
- [ ] `list.order()`
- [ ] `list.arrange()`

# Question 12
What does the `count()` method of a list return?
- [ ] The length of the list
- [ ] The position of an element in the list
- [x] The number of occurrences of a specific element in the list
- [ ] A new list with counted elements

# Question 13
How do you create a copy of a list?
- [ ] `new_list = list`
- [x] `new_list = list.copy()` or `new_list = list[:]` or `new_list = list(list)`
- [ ] `new_list = copy(list)`
- [ ] Lists are automatically copied when assigned to a new variable

# Question 14
What is the output of the following code?
```python
numbers = [1, 2, 3, 4, 5]
numbers.reverse()
print(numbers)
```
- [ ] [1, 2, 3, 4, 5]
- [x] [5, 4, 3, 2, 1]
- [ ] None
- [ ] [1, 3, 5]

# Question 15
How do you create a tuple with a single element?
- [ ] `single_tuple = (1)`
- [x] `single_tuple = (1,)` or `single_tuple = 1,`
- [ ] `single_tuple = Tuple(1)`
- [ ] `single_tuple = tuple[1]`

# Question 16
What is the output of the following code?
```python
t = (1, 2, 3, 4, 5)
print(t[1:4])
```
- [ ] (1, 2, 3, 4)
- [x] (2, 3, 4)
- [ ] [2, 3, 4]
- [ ] An error is raised

# Question 17
Which of the following operations is NOT possible with tuples?
- [ ] Slicing (`tuple[1:3]`)
- [ ] Concatenation (`tuple1 + tuple2`)
- [x] Adding elements (`tuple.append(element)`)
- [ ] Determining length (`len(tuple)`)

# Question 18
What does the following code do?
```python
x, y, z = (1, 2, 3)
```
- [ ] An error is raised
- [x] The variables x, y, and z are assigned the values 1, 2, and 3 respectively
- [ ] x gets the value (1, 2, 3), y and z remain undefined
- [ ] All three variables get the value (1, 2, 3)

# Question 19
Which of the following statements about dictionaries is correct?
- [ ] Dictionaries are always sorted alphabetically by keys
- [ ] Dictionaries can only use strings as keys
- [x] Dictionaries consist of key-value pairs and provide fast access to values based on their keys
- [ ] Dictionaries cannot be nested (no dictionary within a dictionary)

# Question 20
How do you add a new key-value pair to an existing dictionary?
- [x] `dict[new_key] = new_value`
- [ ] `dict.append(new_key, new_value)`
- [ ] `dict.add(new_key, new_value)`
- [ ] `dict.insert(new_key, new_value)`

# Question 21
What is the output of the following code?
```python
person = {"name": "Max", "age": 30}
print(person.get("occupation", "Not specified"))
```
- [ ] A KeyError is raised
- [ ] None
- [x] Not specified
- [ ] occupation

# Question 22
Which method removes all elements from a dictionary?
- [ ] `remove_all()`
- [ ] `delete()`
- [x] `clear()`
- [ ] `reset()`

# Question 23
What is the output of the following code?
```python
colors = {"red": "#FF0000", "green": "#00FF00", "blue": "#0000FF"}
for item in colors:
    print(item)
```
- [ ] #FF0000, #00FF00, #0000FF
- [x] red, green, blue
- [ ] red: #FF0000, green: #00FF00, blue: #0000FF
- [ ] An error is raised

# Question 24
How do you access all keys of a dictionary?
- [ ] `dict.keys`
- [x] `dict.keys()`
- [ ] `dict.get_keys()`
- [ ] `keys(dict)`

# Question 25
What is the output of the following code?
```python
d = {"a": 1, "b": 2}
d.update({"b": 3, "c": 4})
print(d)
```
- [ ] {"a": 1, "b": 2, "c": 4}
- [x] {"a": 1, "b": 3, "c": 4}
- [ ] {"a": 1, "b": 2, "b": 3, "c": 4}
- [ ] An error is raised

# Question 26
How do you create an empty set in Python?
- [ ] `my_set = {}`
- [x] `my_set = set()`
- [ ] `my_set = Set()`
- [ ] `my_set = new Set()`

# Question 27
What is the output of the following code?
```python
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
print(set1 | set2)
```
- [ ] {1, 2, 3, 4, 5, 4, 5, 6, 7, 8}
- [x] {1, 2, 3, 4, 5, 6, 7, 8}
- [ ] {4, 5}
- [ ] An error is raised

# Question 28
Which operation corresponds to the intersection of two sets?
- [ ] `set1 | set2`
- [x] `set1 & set2`
- [ ] `set1 - set2`
- [ ] `set1 ^ set2`

# Question 29
What is the result of the following expression?
```python
{1, 2, 3} - {2, 3, 4}
```
- [x] {1}
- [ ] {4}
- [ ] {1, 4}
- [ ] {1, 2, 3, 4}

# Question 30
What happens when you try to add an element that already exists to a set?
- [ ] An error is raised
- [ ] The element is added a second time
- [x] The element is ignored, the set remains unchanged
- [ ] The element replaces the existing element

# Question 31
How do you check if an element is present in a list?
- [x] `element in list`
- [ ] `list.contains(element)`
- [ ] `list.has(element)`
- [ ] `element.in(list)`

# Question 32
What is the time complexity for the operation `element in list` for a list?
- [ ] O(1)
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Question 33
What is the time complexity for the operation `element in set` for a set?
- [x] O(1)
- [ ] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Question 34
Which code generates a list with the square numbers of the numbers from 1 to 5?
- [ ] `[x² for x in range(1, 6)]`
- [x] `[x**2 for x in range(1, 6)]`
- [ ] `[x*x for x in range(1, 6)]`
- [ ] All of the above answers are correct

# Question 35
What is the output of the following code?
```python
numbers = [1, 2, 3, 4, 5]
doubled = [x * 2 for x in numbers if x % 2 == 0]
print(doubled)
```
- [ ] [2, 4, 6, 8, 10]
- [x] [4, 8]
- [ ] [2, 6, 10]
- [ ] An error is raised

# Question 36
How do you remove duplicates from a list?
- [ ] `list.remove_duplicates()`
- [ ] `remove_duplicates(list)`
- [x] `list(set(my_list))`
- [ ] `list.unique()`

# Question 37
What is the output of the following code?
```python
a = [1, 2, 3]
b = a
b.append(4)
print(a)
```
- [ ] [1, 2, 3]
- [x] [1, 2, 3, 4]
- [ ] [1, 2, 3, [4]]
- [ ] An error is raised

# Question 38
What is the output of the following code?
```python
nested = ([1, 2], [3, 4])
nested[0][1] = 5
print(nested)
```
- [ ] An error is raised because tuples are immutable
- [x] ([1, 5], [3, 4])
- [ ] ([1, 2], [3, 4])
- [ ] [[1, 5], [3, 4]]

# Question 39
Which of the following statements about list comprehensions is correct?
- [ ] List comprehensions can only work with lists, not with other iterable objects
- [ ] List comprehensions are always slower than classic for loops
- [x] List comprehensions provide a compact syntax for creating lists based on existing lists
- [ ] List comprehensions cannot contain conditional statements (if)

# Question 40
What is the value of `result` after executing the following code?
```python
result = [i for i in range(10) if i % 2 == 0 if i % 3 == 0]
```
- [ ] [0, 2, 4, 6, 8]
- [ ] [0, 3, 6, 9]
- [x] [0, 6]
- [ ] [2, 4, 8]

# Question 41
How can you access the last element of a list?
- [ ] `list.last()`
- [x] `list[-1]`
- [ ] `list[len(list)]`
- [ ] `list.end()`

# Question 42
What is the output of the following code?
```python
a = {}
print(type(a))
```
- [ ] <class 'set'>
- [x] <class 'dict'>
- [ ] <class 'list'>
- [ ] <class 'tuple'>

# Question 43
Which of the following operations is not possible with strings in Python?
- [ ] Concatenation with the `+` operator
- [ ] Slicing as with lists
- [x] Changing individual characters (e.g., `s[0] = 'X'`)
- [ ] Iteration with a for loop

# Question 44
What is the output of the following code?
```python
a = {1, 2, 3}
b = {3, 4, 5}
print(a ^ b)
```
- [ ] {1, 2, 4, 5}
- [x] {1, 2, 4, 5}
- [ ] {3}
- [ ] {1, 2, 3, 4, 5}

# Question 45
Which method is used to remove all elements of a set?
- [ ] `remove_all()`
- [ ] `delete()`
- [x] `clear()`
- [ ] `empty()`

# Question 46
What is the output of the following code?
```python
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
print(tuple1 + tuple2)
```
- [ ] An error is raised
- [x] (1, 2, 3, 4, 5, 6)
- [ ] ((1, 2, 3), (4, 5, 6))
- [ ] [1, 2, 3, 4, 5, 6]

# Question 47
How many elements does the set contain after executing the following code?
```python
s = set([1, 2, 3, 2, 3, 4, 5, 4, 3, 2, 1])
```
- [ ] 11
- [ ] 3
- [x] 5
- [ ] An error is raised

# Question 48
Which of the following data structures is best suited for storing a collection of unique elements?
- [ ] List
- [ ] Tuple
- [ ] Dictionary
- [x] Set

# Question 49
What is the result of the following expression?
```python
"Python"[1:4]
```
- [ ] "Python"
- [ ] "Pyt"
- [x] "yth"
- [ ] "ytho"

# Question 50
Which data structure is best suited for storing the frequency of occurrence of words in a text?
- [ ] List
- [ ] Tuple
- [x] Dictionary
- [ ] Set
