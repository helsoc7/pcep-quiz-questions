# Question 1
When is a while loop preferable to a for loop?
- [ ] When the number of iterations is known before the loop begins
- [x] When the number of iterations is not known before the loop begins
- [ ] When a maximum of 5 iterations are needed
- [ ] When iterating over a list

# Question 2
What is the output of the following code?
```python
count = 1
while count < 5:
    print(count, end=" ")
    count += 1
```
- [ ] 1 2 3 4 5
- [x] 1 2 3 4
- [ ] 2 3 4 5
- [ ] 1 3 5 7

# Question 3
What happens if the condition in a while loop never becomes False?
- [ ] The loop automatically terminates after 1000 iterations
- [ ] Python raises a TimeoutError
- [x] An infinite loop is created
- [ ] The loop is not executed at all

# Question 4
What is the output of the following code?
```python
i = 10
while i > 0:
    i -= 2
    if i == 4:
        continue
    print(i, end=" ")
```
- [ ] 8 6 4 2 0
- [ ] 8 6 2 0 -2
- [x] 8 6 2 0
- [ ] 10 8 6 2 0

# Question 5
What does the break statement do in a loop?
- [x] It terminates the loop immediately
- [ ] It jumps to the next iteration of the loop
- [ ] It pauses the loop
- [ ] It resets the loop variable to its initial value

# Question 6
What does the continue statement do in a loop?
- [ ] It terminates the loop immediately
- [x] It jumps to the next iteration of the loop
- [ ] It pauses the loop for one second
- [ ] It increments the loop variable

# Question 7
What is the output of the following code?
```python
for i in range(5):
    if i == 3:
        break
    print(i, end=" ")
```
- [ ] 0 1 2 3 4
- [x] 0 1 2
- [ ] 0 1 2 4
- [ ] 3

# Question 8
How many times is the body of the following loop executed?
```python
for i in range(2, 10, 2):
    print(i)
```
- [ ] 10 times
- [ ] 8 times
- [x] 4 times
- [ ] 5 times

# Question 9
What is the output of the following code?
```python
for i in range(3):
    for j in range(2):
        print(f"{i},{j}", end=" ")
```
- [ ] 0,0 0,1 0,2 1,0 1,1 1,2 2,0 2,1 2,2
- [x] 0,0 0,1 1,0 1,1 2,0 2,1
- [ ] 0,0 1,1 2,2
- [ ] 0,0 0,1 0,2 1,0 1,1 1,2

# Question 10
What does the third parameter in range(1, 10, 2) represent?
- [ ] The number of iterations
- [ ] The end value (inclusive)
- [x] The step size
- [ ] The start value

# Question 11
What is the output of the following code?
```python
for letter in "Python":
    if letter == "h":
        continue
    print(letter, end="")
```
- [ ] Python
- [x] Pyton
- [ ] Pytho
- [ ] ython

# Question 12
Which of the following options is the most efficient method to check if a number is in a large list?
- [ ] Use a for loop and compare each element
- [ ] Use a while loop and compare each element
- [x] Convert the list to a set and use the in operator
- [ ] Use a nested loop

# Question 13
What is the output of the following code?
```python
count = 0
while count < 5:
    count += 1
else:
    print(f"Loop ended at count={count}")
```
- [ ] Loop ended at count=0
- [ ] Loop ended at count=4
- [x] Loop ended at count=5
- [ ] The loop is infinite, there is no output

# Question 14
When is the else block in a while loop NOT executed?
- [ ] When the loop isn't executed at all
- [x] When the loop is terminated with break
- [ ] When the loop is continued with continue
- [ ] When the loop terminates normally

# Question 15
What is the output of the following code?
```python
for i in range(1, 5):
    if i == 3:
        continue
    print(i, end=" ")
else:
    print("End")
```
- [ ] 1 2 3 4 End
- [x] 1 2 4 End
- [ ] 1 2 4
- [ ] 1 2 End

# Question 16
What does the following code do?
```python
while True:
    response = input("Do you want to continue? (y/n): ")
    if response.lower() == 'n':
        break
```
- [ ] The code leads to a syntax error
- [ ] The code is executed only once
- [x] The code repeatedly asks for input until the user enters 'n'
- [ ] The code is executed exactly three times

# Question 17
Which of the following statements about for loops in Python is correct?
- [ ] A for loop can only work with numeric values
- [ ] A for loop cannot be terminated prematurely
- [x] A for loop can iterate over any iterable object
- [ ] A for loop must be executed at least once

# Question 18
What is the output of the following code?
```python
text = "Python"
for i, char in enumerate(text):
    print(f"{i}:{char}", end=" ")
```
- [ ] P:0 y:1 t:2 h:3 o:4 n:5
- [x] 0:P 1:y 2:t 3:h 4:o 5:n
- [ ] 1:P 2:y 3:t 4:h 5:o 6:n
- [ ] P y t h o n

# Question 19
What is the difference between `range(5)` and `range(1, 6)`?
- [ ] There is no difference, both generate the values 1, 2, 3, 4, 5
- [x] `range(5)` generates 0, 1, 2, 3, 4, while `range(1, 6)` generates 1, 2, 3, 4, 5
- [ ] `range(5)` generates 1, 2, 3, 4, 5, while `range(1, 6)` generates 1, 2, 3, 4, 5, 6
- [ ] `range(5)` generates 0, 1, 2, 3, 4, 5, while `range(1, 6)` generates 1, 2, 3, 4, 5

# Question 20
What is the time complexity of a simple iteration over a list with n elements?
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)
- [ ] O(1)

# Question 21
What is the output of the following code?
```python
for i in range(3):
    print(i, end=" ")
    for j in range(2):
        print(j, end=" ")
    print()
```
- [ ] 0 1 2 0 1
- [ ] 0 0 1 1 2 2
- [x] 0 0 1 1 0 1 2 0 1
- [ ] 0 0 0 1 1 0 1 1 2 0 2 1

# Question 22
How can you count backwards from 10 to 1 in Python?
- [ ] `for i in range(10, 1)`
- [ ] `for i in range(10, 1, 1)`
- [x] `for i in range(10, 0, -1)`
- [ ] `for i in range(10, 0)`

# Question 23
What is the output of the following code?
```python
a = [1, 2, 3]
for i in a:
    i = i * 2
print(a)
```
- [x] [1, 2, 3]
- [ ] [2, 4, 6]
- [ ] []
- [ ] An error is generated

# Question 24
How many times is the inner loop executed in the following code?
```python
for i in range(3):
    for j in range(4):
        print(i, j)
```
- [ ] 3 times
- [ ] 4 times
- [ ] 7 times
- [x] 12 times

# Question 25
What is a common reason for unintentional infinite loops?
- [ ] Using `break`
- [ ] Using `continue`
- [x] Forgetting to update the loop variable
- [ ] Using nested loops

# Question 26
Which of the following statements about using `else` with loops is correct?
- [ ] The `else` block is only executed when the loop is terminated with `break`
- [x] The `else` block is only executed when the loop terminates without a `break`
- [ ] The `else` block is executed after each iteration of the loop
- [ ] The `else` block is only executed when the loop condition is `False` from the beginning

# Question 27
What is the output of the following code?
```python
a = 0
while a < 5:
    a += 1
    if a == 3:
        continue
    print(a, end=" ")
```
- [ ] 1 2 3 4 5
- [x] 1 2 4 5
- [ ] 1 2 4
- [ ] 0 1 2 4 5

# Question 28
Which of the following options correctly shows how to iterate over the elements of a dictionary?
- [ ] `for item in dictionary:`
- [ ] `for key, value in dictionary:`
- [x] `for key, value in dictionary.items():`
- [ ] `for item.key, item.value in dictionary:`

# Question 29
How can you start counting from 1 instead of 0 with the `enumerate()` function?
- [ ] `for i, item in enumerate(items, start=1):`
- [x] `for i, item in enumerate(items, 1):`
- [ ] `for i, item in enumerate(1, items):`
- [ ] `for i, item in enumerate(items) + 1:`

# Question 30
What is the time complexity of the following loop?
```python
for i in range(n):
    for j in range(n):
        print(i, j)
```
- [ ] O(n)
- [x] O(n²)
- [ ] O(log n)
- [ ] O(2n)

# Question 31
What is the output of the following code?
```python
for num in range(10, 0, -2):
    print(num, end=" ")
```
- [ ] 10 8 6 4 2 0
- [x] 10 8 6 4 2
- [ ] 8 6 4 2 0
- [ ] 9 7 5 3 1

# Question 32
Which statement best describes the difference between `break` and `continue`?
- [ ] `break` only terminates the current iteration, `continue` terminates the entire loop
- [x] `break` terminates the entire loop, `continue` skips the current iteration
- [ ] `break` only works in for loops, `continue` only works in while loops
- [ ] `break` jumps to the beginning of the loop, `continue` jumps to the end of the loop

# Question 33
What happens if the condition of a while loop is False on the first iteration?
- [ ] The loop is executed once
- [x] The loop is not executed at all
- [ ] A ValueError is raised
- [ ] The loop is executed infinitely

# Question 34
How many values does the call `range(5, 10)` generate?
- [ ] 4
- [x] 5
- [ ] 6
- [ ] 10

# Question 35
What is the output of the following code?
```python
s = "Python"
for char in s[::-1]:
    print(char, end="")
```
- [ ] Python
- [x] nohtyP
- [ ] P y t h o n
- [ ] n o h t y P

# Question 36
Which of the following loops is most efficient for summing all elements of a list?
- [ ] A while loop with an index
- [ ] A for loop with enumerate()
- [x] A for loop over the list
- [ ] All have the same efficiency

# Question 37
What is the value of `result` after executing the following code?
```python
numbers = [1, 2, 3, 4, 5]
result = 0
for num in numbers:
    if num % 2 == 0:
        result += num
```
- [ ] 15
- [x] 6
- [ ] 9
- [ ] 0

# Question 38
Which mechanism can be used to safely implement an infinite loop?
- [ ] Using `while 1 == 1:`
- [x] Using `while True:` with a `break` condition
- [ ] Using a for loop without updating the loop variable
- [ ] Using the `infinity` function

# Question 39
What is the difference between `range(0, 5)` and `range(0, 5, 1)`?
- [x] There is no functional difference
- [ ] `range(0, 5)` includes 5, while `range(0, 5, 1)` ends at 4
- [ ] `range(0, 5)` generates exactly 5 values, while `range(0, 5, 1)` generates 6 values
- [ ] `range(0, 5, 1)` can only be used in for loops

# Question 40
Which types of data structures can be traversed with a for loop?
- [ ] Only lists and tuples
- [ ] Only strings and lists
- [ ] Only iterable objects with numeric indices
- [x] All iterable objects (lists, tuples, strings, dictionaries, sets, etc.)

# Question 41
What is the output of the following code?
```python
d = {"a": 1, "b": 2, "c": 3}
for k in d:
    print(k, end=" ")
```
- [ ] 1 2 3
- [x] a b c
- [ ] a:1 b:2 c:3
- [ ] a,1 b,2 c,3

# Question 42
How can you implement a for loop that processes every second element of a list?
- [ ] `for item in list[::2]:`
- [x] `for item in list[::2]:`
- [ ] `for item in list[1::2]:`
- [ ] `for i in range(len(list)): if i % 2 == 0: item = list[i]`

# Question 43
What is the output of the following code?
```python
total = 0
for i in range(1, 6):
    if i % 2 == 0:
        continue
    total += i
print(total)
```
- [ ] 15
- [x] 9
- [ ] 6
- [ ] 10

# Question 44
In a nested loop, which loop is affected by a `break` statement?
- [x] The immediately surrounding loop
- [ ] All surrounding loops
- [ ] The outermost loop
- [ ] It depends on the type of loop (for or while)

# Question 45
What is the output of the following code?
```python
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

for num in range(10, 20):
    if is_prime(num):
        print(num, end=" ")
```
- [ ] 11 13 17 19 23 29
- [x] 11 13 17 19
- [ ] 10 11 13 17 19
- [ ] There is no output

# Question 46
Which of the following options for iterating over a dictionary returns both keys and values?
- [ ] `for item in dict:`
- [ ] `for key, dict[key] in dict:`
- [x] `for key, value in dict.items():`
- [ ] `for key in dict.keys(): value = dict[key]`

# Question 47
What does the following code calculate?
```python
n = 5
result = 1
for i in range(1, n + 1):
    result *= i
print(result)
```
- [ ] The sum of numbers from 1 to n
- [x] The factorial of n (n!)
- [ ] n to the power of n (n^n)
- [ ] The nth prime number

# Question 48
How can you measure the runtime of a loop?
- [ ] By counting the loop iterations
- [x] By using the `time` module and measuring before and after the loop
- [ ] By analyzing the bytecode
- [ ] By using the built-in `measure()` function

# Question 49
What is the time complexity of the following operation?
```python
if element in large_list:  # large_list has n elements
    print("Element found")
```
- [ ] O(1)
- [x] O(n)
- [ ] O(log n)
- [ ] O(n²)

# Question 50
Which of the following methods is most efficient for checking if an element is present in a large collection of data?
- [ ] Using a for loop and comparing each element
- [ ] Using the list.index() method and catching a possible ValueError
- [x] Converting the collection to a set and using the in operator
- [ ] Sorting the collection and using a binary search
